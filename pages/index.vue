<template>
    <div class="intro" style="background-color:#0095ff">
        <div class="text-center">
            <h2>Isi kunjungan</h2>
            <div class="container-fluid">
              <form class="py-3 m-5">
                <div class="row m-3 d-flex justify-content-center">
                  <div class="col-sm-10">
                        <input type="text" style="box-shadow: 2px 2px 2px #424242;" class="form-control" placeholder="Nama ..." aria-label="Nama ..." />
                      </div>
                    </div>
                  <div class="row m-3 justify-content-center">
                    <div class="col-sm-10">
                        <select class="form-control form-control-lg form-select" style="box-shadow: 2px 2px 2px #424242;">
                          <option value="">Kategori ...</option>
                          <option>Siswa</option>
                          <option>Guru</option>
                          <option>Staf</option>
                          <option>Umum</option>
                        </select>
                    </div>
                  </div>
                    <div class="row m-3 justify-content-center">
                      <div class="col-sm-3">
                                <select class="form-select" aria-label="Disabled select example" style="box-shadow: 2px 2px 2px #424242;">
                                    <option value="">Tingkatan</option>
                                    <option value="X">X</option>
                                    <option value="XI">XI</option>
                                    <option value="XII">XII</option>
                                </select>
                            </div>
                            <div class="col-sm-4 justify-content-center">
                                <select class="form-select" aria-label="Disabled select example" style="box-shadow: 2px 2px 2px #424242;">
                                    <option value="">Jurusan</option>
                                    <option value="TJKT">TJKT</option>
                                    <option value="TBSM">TBSM</option>
                                    <option value="PPLG">PPLG</option>
                                    <option value="DKV">DKV</option>
                                    <option value="TOI">TOI</option>
                                </select>
                            </div>
                            <div class="col-sm-3 justify-content-center">
                                <select class="form-select" aria-label="Disabled select example" style="box-shadow: 2px 2px 2px #424242;">
                                    <option value="">Kelas</option>
                                    <option value="1">1</option>
                                    <option value="2">2</option>
                                    <option value="3">3</option>
                                    <option value="4">4</option>
                                </select>
                            </div>
                        </div>
                        <div class="row m-3 justify-content-center">
                            <div class="col-sm-10">
                                <select class="form-control mb-3" style="box-shadow: 2px 2px 2px #424242;">
                                    <option value="">Keperluan ...</option>
                                    <option>Membaca</option>
                                    <option>Meminjam Buku</option>
                                    <option>Berkunjung</option>
                                    <option>Mengembalikan Buku</option>
                                </select>
                            </div>
                        </div>
                        <NuxtLink to="/pengunjung">
                            <input type="submit" class="btn" value="Kirim">
                        </NuxtLink>
                    </form>
                
            </div>
        </div>
    </div>
  </template>