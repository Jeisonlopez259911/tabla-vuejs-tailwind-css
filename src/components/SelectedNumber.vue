<script>
export default {
    data() {
        return {
            rango: Array.from({ length: 100 }, (v, i) => i + 1)
        };
    }

};
</script>

<template>
        <label for="numbers">Filas por pagina: </label>
        <select name="numbers">
            <option class="block w-200 m-20" v-for="numero in rango" :key="numero" :value="numero">{{ numero }}</option>
        </select>
</template>
  
