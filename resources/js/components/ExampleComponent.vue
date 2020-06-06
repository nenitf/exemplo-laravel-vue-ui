<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">header</div>

                    <div class="card-body">
                        <input type="test" v-model="test">
                    </div>
                    {{test}}
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
    data: () => {
    return {

    test: ''
    }
    },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
