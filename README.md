# Tutorial Youtube Belajar Bootstrap 5.x - Membuat Banner

## Live Demo

[Tampilkan Demo](https://janzenfaidiban.github.io/tutorial-belajar-bootstrap-5x-membuat-navbar/)

## Video Tutorial di Youtube

[Tampilkan Video](https://youtu.be/C_fZNx2o_5Y)

## Header

Gunakan codes berikut untuk membuat desain header.

```html
<!-- HEADER START -->
    <header class="bg-light border py-3">

        <!-- .container start -->
        <div class="container">

            <!-- navbar start -->
            <nav class="navbar navbar-expand-lg">
                <div class="container-fluid">
                    <a class="navbar-brand" href="#"><i class="fa-brands fa-pagelines"></i> Toko <span class="fw-bold">Bunga</span></a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                        data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                        aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarSupportedContent">
                        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                            <li class="nav-item">
                                <a class="nav-link active" aria-current="page" href="#">Beranda</a>
                            </li>

                            <li class="nav-item dropdown">
                                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                                    aria-expanded="false">
                                    Produk Bunga
                                </a>
                                <ul class="dropdown-menu">
                                    <li><a class="dropdown-item" href="#">Outdoor</a></li>
                                    <li><a class="dropdown-item" href="#">Gantung</a></li>
                                    <li><a class="dropdown-item" href="#">Bunga Air</a></li>
                                    <li>
                                        <hr class="dropdown-divider">
                                    </li>
                                    <li><a class="dropdown-item" href="#">Lainnya</a></li>
                                </ul>
                            </li>

                            <li class="nav-item">
                                <a class="nav-link" href="#">Hubungi Kami</a>
                            </li>

                            <li class="nav-item">
                                <a class="nav-link" href="#">FAQ</a>
                            </li>

                        </ul>
                        <form class="d-flex" role="search">
                            <input class="form-control me-2" type="search" placeholder="Cari jenis bunga..."
                                aria-label="Search">
                            <button class="btn btn-outline-dark" type="submit">Cari</button>
                        </form>
                    </div>
                </div>
            </nav>
            <!-- navbar end -->

        </div>
        <!-- .container end -->

    </header>
    <!-- HEADER END -->
```
