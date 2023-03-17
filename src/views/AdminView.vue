<template>
    <div class="admin py-5">
        <div class="container">
            <div class="row mb-3">
                <div class="col-md-12">
                    <h5>Halo Admin, Selamat Datang</h5>
                </div>
            </div>
            <div class="row">
                <div class="col-md-4">
                    <div class="card pt-3 pb-2 px-4">
                        <div class="d-flex">
                            <div class="flex-shrink-0">
                                <font-awesome-icon icon="fa-solid fa-user" class="iconhero"/>
                            </div>
                            <div class="flex-grow-1 ms-3">
                                <h5>1029</h5>
                                <p>User Terdaftar</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card pt-3 pb-2 px-4">
                        <div class="d-flex">
                            <div class="flex-shrink-0">
                                <font-awesome-icon icon="fa-solid fa-handshake" class="iconhero"/>
                            </div>
                            <div class="flex-grow-1 ms-3">
                                <h5>5409</h5>
                                <p>Pkerjaan Sukses</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card pt-3 pb-2 px-4">
                        <div class="d-flex">
                            <div class="flex-shrink-0">
                                <font-awesome-icon icon="fa-solid fa-file" class="iconhero"/>
                            </div>
                            <div class="flex-grow-1 ms-3">
                                <h5>478</h5>
                                <p>Pekerjaan Tersedia</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row mt-5">
                <div class="col-md-9">
                    <div class="card pt-3 pb-2 px-3 mb-3">
                        <h5 class="mb-3"><font-awesome-icon icon="fa-solid fa-table"/>  Data Table</h5>
                        <div class="table-responsive">
                            <table class="table table-striped">
                                <thead>
                                    <tr>
                                    <th scope="col">#</th>
                                    <th scope="col">First</th>
                                    <th scope="col">Last</th>
                                    <th scope="col">Handle</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr>
                                    <th scope="row">1</th>
                                    <td>Mark</td>
                                    <td>Otto</td>
                                    <td>@mdo</td>
                                    </tr>
                                    <tr>
                                    <th scope="row">2</th>
                                    <td>Jacob</td>
                                    <td>Thornton</td>
                                    <td>@fat</td>
                                    </tr>
                                    <tr>
                                    <th scope="row">3</th>
                                    <td>Larry</td>
                                    <td>Bird</td>
                                    <td>@twitter</td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card pt-3 pb-2 px-3">
                        <h5 class="mb-3"><font-awesome-icon icon="fa-solid fa-bell"/>  Notifikasi</h5>
                        <ul class="list-group">
                            <li class="list-group-item new-notif"><font-awesome-icon icon="fa-solid fa-file"/> Laporan Penipuan Tawaran Pekerjaan</li>
                            <li class="list-group-item">Laporan Bug</li>
                            <li class="list-group-item">Pemberitahuan 1000 User</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
.admin{
    background: #f8faff;
}

.admin .card{
    border: none;
    background: #fff;
}
thead{
    background-color: #F53838;
    color: white;
}
.new-notif{
    background: #F53838;
    color: white;
}
</style>