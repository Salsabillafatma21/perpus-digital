<template>
    <div>
        <div class="container-fluid">
            <div class="row py-5">
                <div class="col-lg-6">
                    <nuxt-link to="/pengunjung/tambah">
                        <div class="card bg-pengunjung rounded-5">
                            <div class="card-body">
                                <h2 class="fw-bold">Pengunjung</h2>
                            </div>
                        </div>
                    </nuxt-link>
            </div>
            <div class="col-lg-6">
                <nuxt-link to="/buku">
                    <div class="card bg-buku rounded-5">
                        <div class="card-body">
                            <h2>cari buku</h2>
                        </div>
                    </div>
                </nuxt-link>
        </div>
        <h2>Statistik</h2>
        <div class="row py-5">
            <nuxt-link to="/pengunjung/index"></nuxt-link>
            <div class="col-lg-6">
                <nuxt-link to="/pengunjung/index">
                    <div class="card pengunjung rounded-5">
                        <div class="card-body">
                            <h2>Isi buku kunjungan</h2>
                        </div>
                    </div>
                </nuxt-link>
            </div>

            <div class="col-lg-6">
                <nuxt-link to="/buku">
                    <div class="card buku rounded-5">
                        <div class="card-body">
                            <h2>50 Buku</h2>
                        </div>
                    </div>
                </nuxt-link>
            </div>
        </div>
    </div>
        </div>
    </div>
</template>

<style scoped>
.container-fluid {
    /* padding: 0;
    margin: 0; */
    background-color: #353D84;
}

.card {
    height: 250px;
    box-shadow: 1px 1px 10px hsl(0, 0%, 100%)
}

.card.bg-pengunjung {
    background-image: url('../assets/img/pengunjung.jpeg');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
}

.card.bg-buku {
    background: url('../assets/img/cari buku.jpeg') no-repeat center center;
    background-size: cover;
}

.pengunjung {
    background-color: #C49DC0;
}

.buku {
    background-color: #C49DC0;
}
</style>
