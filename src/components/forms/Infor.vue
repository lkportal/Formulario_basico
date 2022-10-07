<template>
    <div>
        <form>
            <div>
                <Formulario/>
            </div>
            <div>
                <InputText/>
            </div>

        </form>
    </div>
</template>

<script>
import Formulario from './Formulario.vue'
import InputText from './InputText.vue'

export default{
    name:'Infor',
    components:{
        Formulario, InputText
    }
}
</script>