<template>
    <div class="container">
        <h4 class="mt-5">Identitas Sekolah</h4>
        <div class="text-center">
            <img class="image mt-5" src="/assets/logosmk4.png" alt="" width="15%">
        </div>
    </div>
    <div class="card  shadow small mt-5 mb-5">
        <table class="table table-striped">
        <!-- <thead>
        <tr>
        <th scope="col">First</th>
        <th scope="col">Last</th>
        </tr>
    </thead> -->
        <tbody>
        <tr>
            <td>NPSN</td>
                <td>{{ data.npsn }}</td>
            </tr>
            <tr>
                <td>Tanggal SK Pendirian</td>
                <td>{{ data.sk }}</td>
            </tr>
            <tr>
                <td>Nama Sekolah</td>
                <td>{{ data.name }}</td>
            </tr>
            <tr>
                <td>Alamat</td>
                <td>{{ data.address }}</td>
            </tr>
            <tr>
                <td>Kelurahan</td>
                <td>{{ data.kelurahan }}</td>
            </tr>
            <tr>
                <td>Kecamatan</td>
                <td>{{ data.kecamatan }}</td>
            </tr>
            <tr>
                <td>Kota</td>
                <td>{{ data.kota }}</td>
            </tr>
            <tr>
                <td>Kode POS</td>
                <td>{{ data.kp }}</td> 
            </tr>
            <tr>
                <td>Provinsi</td>
                <td>{{ data.provinsi }}</td>
            </tr>
            <tr>
                <td>Telepon/Fax</td>
                <td>{{ data.tp }}</td>
            </tr>
            <tr>
                <td>Email</td>
                <td>{{ data.email }}</td>
            </tr>
        </tbody>
    </table>
        <div class="content">
            <div class="card mt-5 mb-5 shadow">
                <div class="card-header">
                    <h5 class="text-center">Sejarah Singkat SMK Negeri 4 Tasikmalaya</h5>
                </div>
                <div class="card-body">
                    <p class="card-text">Sejalan dengan Program Pemerintah dibidang pendidikan Menengah Kejuruan
                        pada saat itu
                        yakni pemerataan akses ditambah pula dengan banyaknya keinginan masyarakat yang mengharapkan
                        adanya SMK
                        Negeri di daerah Kecamatan Purbaratu Kota  Tasikmalaya, terutama untuk menampung tamatan
                        dari SLTP yang
                        ingin melanjutkan ke SMK maka beberapa tokoh masyarakat, unsur pejabat pemerintah di
                        Kecamatan Purbaratu
                        Kota Tasikmalaya mengusulkan kepada pemerintah Kota Tasikmalaya dan Pemerintah Provinsi Jawa
                        Barat, agar
                        berdirinya SMK Negeri di Kecamatan Purbaratu Kota Tasikmalaya.
                        Setelah melalui perjuangan yang sangat panjang dari berbagai pihak khususnya Disdik Kota
                        Tasikmalaya dan
                        pihak-pihak terkait lainnya sesuai prosedur dan ketentuan yang berlaku pada waktu itu dengan
                        mengucapkan
                        syukur Alhamdulillah akhirnya pada tahun pelajaran 2010/2011 SMK Negeri 4 Tasikmalaya mulai
                        berdiri, pada
                        awalnya membuka Kompetensi Keahlian Teknik Komputer dan Jaringan dengan pendaftar peserta
                        Didik Baru pada
                        waktu itu berjumlah 44 orang. Pada awalnya tempat belajar menumpang di SMP Negeri 17 Kota
                        Tasikmalaya, dan
                        sekolah induknya adalah SMK Negeri 2 Kota Tasikmalaya, Untuk Tenaga pendidik dan Tenaga
                        Kependidikan masih
                        dibantu sepenuhnya oleh kedua sekolah tersebut.
                        Pada tahun 2012 keluarlah surat Izin Pendirian berdasarkan keputusan kepala Badan Pelayanan
                        Perizinan
                        Terpadu Kota Tasikmalaya No. 420/9/SK-BPPT/2012 Tanggal 06 Februari 2012.</p>
                </div>
            </div>
        </div>

    </div>
    <.
</template>

<style scoped>
h4 {
    font-family: "Poppins", serif;
    margin-right: auto;
}

.card {
    width: 70%;
    margin: auto;
}
</style>

<script setup>
const data = {
    name: "SMKN 4 Tasikmalaya",
    npsn: "20276063",
    sk:"06 Februari 2012",
    kelurahan:"Sukamenak",
    kecamatan:"Purbaratu",
    kota:"Tasikmalaya, Jawa Barat",
    tp: "401327810004",
    kp:"46196",
    provinsi:"Jawa Barat",
    address: "Jl Depok RT 02 RW 05, ",
    email: "info@smkn4-tsm.sch.id",
    establishmentSKNumber: "420/9/SK-BPPT/2012",
    establishmentDate: "06 Februari 2012"
};
</script>