<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <Header />
                    <div class="card-header">Benvenuto</div>

                    <div class="card-body">
                        Sito in costruzione
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import Header from '../components/Header.vue';

    export default {
        name: 'App',

        components: {
            Header,
        }
    }
</script>
