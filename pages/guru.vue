<template>
    <div class="container mt-5">
        <h1 class="text-center mb-4">Daftar Guru</h1>
        <div class="card-body">
        <div class="row gap-5">
            <div v-for="(guru, index) in displayedGuruList" :key="index" class="card guru-card mx-3">
            <div class="card-body">
                <img :src="guru.foto" class="card-img-top" alt="Foto Guru" />
                <h5 class="card-title">{{ guru.nama }}</h5>
                <p class="card-text">{{ guru.mapel }}</p>
            </div>
            </div>
        </div>
        </div>
        <div class="text-center mt-4" v-if="displayedGuruList.length < guruList.length">
        <button @click="loadMore" class="btn btn-primary">Lainnya</button>
        </div>
    </div>
    </template>

    <script setup>
    import { ref } from 'vue';
    
    import guru1 from "/assets/deni.jpg";
    import guru2 from "/assets/arip.jpg";
    import guru3 from "/assets/gandi.jpg";
    import guru4 from "/assets/zul.jpg";
    import guru5 from "/assets/taufik.jpg";
    import guru6 from "/assets/andi.jpg";
    import guru7 from "/assets/adi.jpg";
    import guru8 from "/assets/lisye.jpg";
    import guru9 from "/assets/vina.jpg";
    import guru10 from "/assets/tini.jpg";
    import guru11 from "/assets/sri.jpg";
    import guru12 from "/assets/lisna.jpg";
    import guru13 from "/assets/joy.jpg";
    import guru14 from "/assets/suminar.jpg";
    
    
const guruList = [
    { nama: "DENI MAULANA ", mapel: "B . Inggris", foto: guru1 },
    { nama: "ARIP ", mapel: "B . Inggris", foto: guru2 },
    { nama: "BINTANG ", mapel: "B . Inggris", foto: guru3 },
    { nama: "ZUL HILMI ", mapel: "B . Inggris", foto: guru4 },
    { nama: "TAUFIK HIDAYAT ", mapel: "B . Inggris", foto: guru5 },
    { nama: "ANDI ", mapel: "B . Inggris", foto: guru6 },
    { nama: "ADI IASAN ", mapel: "B . Inggris", foto: guru7 },
    { nama: "LISYE DIANA ", mapel: "B . Inggris", foto: guru8 },
    { nama: "VINA ", mapel: "B . Inggris", foto: guru9 },
    { nama: "TINI ", mapel: "B . Inggris", foto: guru10 },
    { nama: "SRI ", mapel: "B . Inggris", foto: guru11 },
    { nama: "LISNA ", mapel: "B . Inggris", foto: guru12 },
    { nama: "JOY ", mapel: "B . Inggris", foto: guru13 },
    { nama: "SUMINAR ", mapel: "B . Inggris", foto: guru14 },
];
        
    
    const displayedGuruList = ref(guruList.slice(0, 4)); 
    
    const loadMore = () => {
    const currentLength = displayedGuruList.value.length;
    const nextGuruList = guruList.slice(currentLength, currentLength + 4);
    displayedGuruList.value.push(...nextGuruList);
    };
    </script>
    
    <style scoped>
.container {
    margin-bottom: 70px;
}
    
.guru-card {
    min-width: 262px;
    max-width: 230px;
    flex: 0 0 auto;
    border: 1px solid #ddd;
    border-radius: 5px;
}
    
.card-img-top {
    width: 100%;
    height: 220px;
    object-fit: cover;
}
    
.card-body {
    text-align: center;
}
</style>