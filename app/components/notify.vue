<template>
    <div>
        <p>Estoy en notify</p>
        <button @click="mostrarExito">
            Guardar
        </button>

        <button type="click" @click="mostrarError">
            Error
        </button>
    </div>
</template>

<script setup>
    const toast = useToast()

    toast.success('Saved', 'Your changes were saved.')
    toast.error('Error', 'Something went wrong.')
    toast.info('Heads up', 'New version is available.')
    toast.warning('Careful', 'This action cannot be undone.')

    const mostrarExito = () => {
        toast.success('Saved', 'Your changes were saved.')
    }

    function mostrarError() {
        toast.error('Error', 'Something went wrong.')
    }

</script>
