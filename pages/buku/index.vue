<template>
    <div class="container-fluid">
        <div class="row content">
            <div class="col-lg-12">
                <h2 class="text-center my-4" style="color: aliceblue;">RAK BUKU</h2>
                <div class="my-3 d-flex justify-content-center">
                    <input type="search" class="form-control rounded-5 cari" placeholder="SEARCH?..." style="background-color: #6C73B2;">
                </div>
                <div class="my-3 text-muted"></div>
                <div class="row layer m-5 rounded-5">
                    <h1 class="text-center" style="color: #6C73B2">Koleksi Buku</h1>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="../assets/img/k.jpeg" class="cover" alt="cover 1" style="width: 100%;">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="../assets/img/p.jpeg" class="cover" alt="cover 2" style="width: 100%;">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="../assets/img/n.jpeg" class="cover" alt="cover 3" style="width: 100%;">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="../assets/img/h.jpeg" class="cover" alt="cover 3" style="width: 100%;">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>

.content {
    background-color: #C49DC0;
};


.cari{
    width: 40rem;
}
/* .cover{
    height: 50%;
    width: 50%;
} */
.layer {
    background-color: #6C73B2;
}
</style>