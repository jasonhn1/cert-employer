
<!-- <script>
export default {
  count 
}
</script> -->

<template>
  <!-- Begin page -->
    <div id="wrapper">

        <!-- Top Bar Start -->
        <div class="topbar">

            <!-- LOGO -->
            <div class="topbar-left">
                <a href="#" class="logo">
                    <span class="logo-light">
                            Certitude
                        </span>
                    <span class="logo-sm">
                            C
                        </span>
                </a>
            </div>

            <nav class="navbar-custom">
                <ul class="navbar-right list-inline float-right mb-0">
                  
                    <li class="dropdown notification-list list-inline-item">
                        <div class="dropdown notification-list nav-pro-img">
                            <a class="dropdown-toggle nav-link arrow-none nav-user" data-toggle="dropdown" href="#" role="button" aria-haspopup="false" aria-expanded="false">
                                <img src="assets/images/user-4.jpg" alt="user" class="rounded-circle">
                            </a>
                            <div class="dropdown-menu dropdown-menu-right profile-dropdown ">
                                <!-- item-->
                                <a class="dropdown-item" href="#"><i class="mdi mdi-account-circle"></i> Profile</a>
                                <div class="dropdown-divider"></div>
                                <a class="dropdown-item text-danger" href="#"><i class="mdi mdi-power text-danger"></i> Logout</a>
                            </div>
                        </div>
                    </li>

                </ul>

                <ul class="list-inline menu-left mb-0">
                    <li class="float-left">
                        <button class="button-menu-mobile open-left waves-effect">
                            <i class="mdi mdi-menu"></i>
                        </button>
                    </li>
                    <li class="d-none d-md-inline-block">
                        <form role="search" class="app-search">
                            <div class="form-group mb-0">
                                <input type="text" class="form-control" placeholder="Search..">
                                <button type="submit"><i class="fa fa-search"></i></button>
                            </div>
                        </form>
                    </li>
                </ul>

            </nav>

        </div>
        <!-- Top Bar End -->

        <!-- ========== Left Sidebar Start ========== -->
        <div class="left side-menu">
            <div class="slimscroll-menu" id="remove-scroll">

                <!--- Sidemenu -->
                <div id="sidebar-menu">
                    <!-- Left Menu Start -->
                    <ul class="metismenu" id="side-menu">
                        <li class="menu-title">Menu</li>
                        <li>
                            <a href="#" class="waves-effect">
                                <i class="icon-accelerator"></i><span> Dashboard </span>
                            </a>
                        </li>


                        <li>
                          <a  href="calendar.html" class="waves-effect"><i class="icon-calendar"></i><span> Expired </span></a>
                      </li>

                        <li>
                            <a  href="calendar.html" class="waves-effect"><i class="icon-paper-sheet"></i><span>Analytics </span></a>
                        </li>


                       
                    </ul>

                </div>
                <!-- Sidebar -->
                <div class="clearfix"></div>

            </div>
            <!-- Sidebar -left -->

        </div>
        <!-- Left Sidebar End -->

        <!-- ============================================================== -->
        <!-- Start right Content here -->
        <!-- ============================================================== -->
        <div class="content-page">
            <!-- Start content -->
            <div class="content">
                <div class="container-fluid">
                    <div class="page-title-box">
                        <div class="row align-items-center">
                            <div class="col-sm-6">
                                <h4 class="page-title">Dashboard nuts</h4>
                            </div>
                            <div class="col-sm-6">
                                <ol class="breadcrumb float-right">
                                    <li class="breadcrumb-item"><a href="#">Certitude</a></li>
                                    <li class="breadcrumb-item active">Dashboard</li>
                                </ol>
                            </div>
                        </div>
                        <!-- end row -->
                    </div>
                    <!-- end page-title -->

                    <div class="row">

                        <div class="col-sm-6 col-xl-3">
                            <div class="card">
                                <div class="card-heading p-4">
                                    <div class="mini-stat-icon float-right">
                                        <i class="mdi mdi-cube-outline bg-primary  text-white"></i>
                                    </div>
                                    <div>
                                        <h5 class="font-16">Active Sessions</h5>
                                    </div>
                                    <h3 class="mt-4">43,225</h3>
                                    <div class="progress mt-4" style="height: 4px;">
                                        <div class="progress-bar bg-primary" role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                                    </div>
                                    <p class="text-muted mt-2 mb-0">Previous period<span class="float-right">75%</span></p>
                                </div>
                            </div>
                        </div>

                        <div class="col-sm-6 col-xl-3">
                            <div class="card">
                                <div class="card-heading p-4">
                                    <div class="mini-stat-icon float-right">
                                        <i class="mdi mdi-briefcase-check bg-success text-white"></i>
                                    </div>
                                    <div>
                                        <h5 class="font-16">Total Revenue</h5>
                                    </div>
                                    <h3 class="mt-4">$73,265</h3>
                                    <div class="progress mt-4" style="height: 4px;">
                                        <div class="progress-bar bg-success" role="progressbar" style="width: 88%" aria-valuenow="88" aria-valuemin="0" aria-valuemax="100"></div>
                                    </div>
                                    <p class="text-muted mt-2 mb-0">Previous period<span class="float-right">88%</span></p>
                                </div>
                            </div>
                        </div>

                        <div class="col-sm-6 col-xl-3">
                            <div class="card">
                                <div class="card-heading p-4">
                                    <div class="mini-stat-icon float-right">
                                        <i class="mdi mdi-tag-text-outline bg-warning text-white"></i>
                                    </div>
                                    <div>
                                        <h5 class="font-16">Average Price</h5>
                                    </div>
                                    <h3 class="mt-4">447</h3>
                                    <div class="progress mt-4" style="height: 4px;">
                                        <div class="progress-bar bg-warning" role="progressbar" style="width: 68%" aria-valuenow="68" aria-valuemin="0" aria-valuemax="100"></div>
                                    </div>
                                    <p class="text-muted mt-2 mb-0">Previous period<span class="float-right">68%</span></p>
                                </div>
                            </div>
                        </div>

                        <div class="col-sm-6 col-xl-3">
                            <div class="card">
                                <div class="card-heading p-4">
                                    <div class="mini-stat-icon float-right">
                                        <i class="mdi mdi-buffer bg-danger text-white"></i>
                                    </div>
                                    <div>
                                        <h5 class="font-16">Add to Card</h5>
                                    </div>
                                    <h3 class="mt-4">86%</h3>
                                    <div class="progress mt-4" style="height: 4px;">
                                        <div class="progress-bar bg-danger" role="progressbar" style="width: 82%" aria-valuenow="82" aria-valuemin="0" aria-valuemax="100"></div>
                                    </div>
                                    <p class="text-muted mt-2 mb-0">Previous period<span class="float-right">82%</span></p>
                                </div>
                            </div>
                        </div>

                    </div>


                    <!-- START ROW -->
                    <div class="row">
                        <div class="col-xl-12">
                            <div class="card m-b-30">
                                <div class="card-body">
                                    <h4 class="mt-0 header-title mb-4">Active Deals</h4>
                                    <div class="table-responsive">
                                        <table class="table table-hover">
                                            <thead>
                                                <tr>
                                                    <th scope="col">Name</th>
                                                    <th scope="col">Status</th>
                                                    <th scope="col">Amount</th>
                                                    <th scope="col">Contact</th>
                                                    <th scope="col">Location</th>
                                                    <th scope="col" colspan="2">Date</th>

                                                </tr>
                                            </thead>
                                            <tbody>
                                                <tr>
                                                    <td>Jassa</td>
                                                    <td><span class="badge badge-success">Delivered</span></td>
                                                    <td>$9,420,000</td>
                                                    <td>
                                                        <div>
                                                            <img src="assets/images/user-2.jpg" alt="" class="thumb-md rounded-circle mr-2"> Jassa
                                                        </div>
                                                    </td>
                                                    <td>Ludhiana</td>
                                                    <td>15/1/2021</td>

                                                    <td>
                                                        <div>
                                                            <a href="#" class="btn btn-primary btn-sm">Edit</a>
                                                        </div>
                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>Jassa</td>
                                                    <td><span class="badge badge-warning">Pending</span></td>
                                                    <td>$3,120,000</td>
                                                    <td>
                                                        <div>
                                                            <img src="assets/images/user-3.jpg" alt="" class="thumb-md rounded-circle mr-2"> Jassa
                                                        </div>
                                                    </td>
                                                    <td>Ludhiana</td>
                                                    <td>16/1/2021</td>

                                                    <td>
                                                        <div>
                                                            <a href="#" class="btn btn-primary btn-sm">Edit</a>
                                                        </div>
                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>Jassa</td>
                                                    <td><span class="badge badge-success">Delivered</span></td>
                                                    <td>$6,360,000</td>
                                                    <td>
                                                        <div>
                                                            <img src="assets/images/user-4.jpg" alt="" class="thumb-md rounded-circle mr-2"> Jassa
                                                        </div>
                                                    </td>
                                                    <td>Ludhiana</td>
                                                    <td>17/1/2021</td>

                                                    <td>
                                                        <div>
                                                            <a href="#" class="btn btn-primary btn-sm">Edit</a>
                                                        </div>
                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>Jassa</td>
                                                    <td><span class="badge badge-danger">Cancel</span></td>
                                                    <td>$5,200,000</td>
                                                    <td>
                                                        <div>
                                                            <img src="assets/images/user-5.jpg" alt="" class="thumb-md rounded-circle mr-2"> Jassa
                                                        </div>
                                                    </td>
                                                    <td>Ludhiana</td>
                                                    <td>18/1/2021</td>

                                                    <td>
                                                        <div>
                                                            <a href="#" class="btn btn-primary btn-sm">Edit</a>
                                                        </div>
                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>Jassa</td>
                                                    <td><span class="badge badge-success">Delivered</span></td>
                                                    <td>$7,250,000</td>
                                                    <td>
                                                        <div>
                                                            <img src="assets/images/user-6.jpg" alt="" class="thumb-md rounded-circle mr-2"> Jassa
                                                        </div>
                                                    </td>
                                                    <td>Ludhiana</td>
                                                    <td>19/1/2021</td>

                                                    <td>
                                                        <div>
                                                            <a href="#" class="btn btn-primary btn-sm">Edit</a>
                                                        </div>
                                                    </td>
                                                </tr>
                                            </tbody>
                                        </table>
                                    </div>

                                </div>
                            </div>
                        </div>

                    </div>
                    <!-- END ROW -->

                </div>
                <!-- container-fluid -->

            </div>
            <!-- content -->



        </div>
        <!-- ============================================================== -->
        <!-- End Right content here -->
        <!-- ============================================================== -->

    </div>
    <!-- END wrapper -->
</template>