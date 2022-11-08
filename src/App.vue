
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
                                <h4 class="page-title">Dashboard</h4>
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


                    <!-- START ROW -->
                    <div class="row">
                      <div class="col-xl-12">
                          <div class="card m-b-30">
                              <div class="card-body">
                                  <h4 class="mt-0 header-title mb-4">Candidate Links</h4>
                                  <div class="table-responsive">
                                      <table class="table table-hover">
                                          <thead>
                                              <tr>
                                                  <th scope="col">Name</th>
                                                  <th scope="col">Status</th>
                                                  <th scope="col">Location</th>
                                                  <th scope="col" colspan="2">Date</th>

                                              </tr>
                                          </thead>
                                          <tbody>
                                              <tr>
                                                  <td>Jason Nguyen</td>
                                                  <td><span class="badge badge-success">Ready</span></td>
                                       
                                                  <td>USA</td>
                                                  <td>12/1/2021</td>

                                                  <td>
                                                      <div>
                                                          <a href="#" class="btn btn-primary btn-sm ">View</a>
                                                      </div>
                                                  </td>
                                              </tr>
  
                                              <tr>
                                                  <td>Tim Chen</td>
                                                  <td><span class="badge badge-success">Ready</span></td>
                                    
                                                  <td>USA</td>
                                                  <td>1/1/2021</td>

                                                  <td>
                                                      <div>
                                                          <a href="#" class="btn btn-primary btn-sm">View</a>
                                                      </div>
                                                  </td>
                                              </tr>
                                              
                                              <tr>
                                                  <td>John Doe</td>
                                                  <td><span class="badge badge-success">Ready</span></td>
                                                  <td>USA</td>
                                                  <td>1/1/2021</td>

                                                  <td>
                                                      <div>
                                                          <a href="#" class="btn btn-primary btn-sm">View</a>
                                                      </div>
                                                  </td>
                                              </tr>
                                              <tr>
                                                <td>Ben Mueller</td>
                                                <td><span class="badge badge-danger">Expired</span></td>
                                                
                    
                                                <td>USA</td>
                                                <td>1/1/2021</td>

                                                <td>
                                                    <div>
                                                        <a href="#" class="btn btn-primary btn-sm disabled">View</a>
                                                    </div>
                                                </td>
                                            </tr>
                                            <tr>
                                              <td>Jeffery Hover</td>
                                              <td><span class="badge badge-warning ">Waiting</span></td>
                                              
                                
                                              <td>USA</td>
                                              <td>12/12/2021</td>

                                              <td>
                                                  <div>
                                                      <a href="#" class="btn btn-primary btn-sm disabled">View</a>
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



                    <div class="row">

                        <div class="col-sm-6 col-xl-3">
                            <div class="card">
                                <div class="card-heading p-4">
                                    <div class="mini-stat-icon float-right">
                                        <i class="mdi mdi-cube-outline bg-primary  text-white"></i>
                                    </div>
                                    <div>
                                        <h5 class="font-16">Active Links</h5>
                                    </div>
                                    <h3 class="mt-4">43,225</h3>
                                    <div class="progress mt-4" style="height: 4px;">
                                        <div class="progress-bar bg-primary" role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                                    </div>
                                    <p class="text-muted mt-2 mb-0">Viewed<span class="float-right">75%</span></p>
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
                                        <h5 class="font-16">Read Links</h5>
                                    </div>
                                    <h3 class="mt-4">447</h3>

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
                                        <h5 class="font-16">Expired Links</h5>
                                    </div>
                                    <h3 class="mt-4">84</h3>
                                   
                                </div>
                            </div>
                        </div>

                    </div>


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