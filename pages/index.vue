<template>
    <div>
        <div class="container-fluid">
            <div class="row 2 py-5">
                <div class="col-lg-8">
                    <nuxt-link to="/pengunjung/tambah">
                        <div class="card bg-pengunjung rounded-5">
                            <div class="card-body">
                                <h2 class="fw-bold">Pengunjung</h2>
                            </div>
                        </div>
                    </nuxt-link>
                </div>
            </div>
            <div class="row justify-content-end">
                <div class="col-lg-8">
                    <nuxt-link to="/buku">
                        <div class="card bg-buku rounded-5">
                            <div class="card-body">
                                <h2>cari buku</h2>
                            </div>
                        </div>
                    </nuxt-link>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.container-fluid {
    /* padding: 0;
    margin: 0; */
    background-color: #C49DC0;
}

.card {
    height: 250px;
    background-color: #353D84;
    box-shadow: 1px 1px 10px (0, 0%, 100%)
}

.card.bg-pengunjung {
    background-image: url('../assets/pengunjung.jpeg');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
}

.card.bg-buku {
    background: url('../assets/caribuku.jpg') no-repeat center center;
    background-size: cover;
}

.pengunjung {
    background-color: #C49DC0;
}

.buku {
    background-color: #353D84;
}
</style>
