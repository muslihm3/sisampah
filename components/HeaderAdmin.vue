<template>
  <nav class="navbar fixed-top navbar-expand-lg bg-body-tertiary mb-5">
    <div class="container">
      <a class="navbar-brand" href="/">
        <img
          src="/image/sisampah-logo.svg"
          height="50"
          alt="sisampah Logo"
          fw-bold
        />sisampah</a
      >
      <!-- Toggle button -->
      <button
        class="navbar-toggler"
        type="button"
        data-mdb-toggle="collapse"
        data-mdb-target="#navbarRightAlignExample"
        aria-controls="navbarRightAlignExample"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <i class="fas fa-bars"></i>
      </button>

      <!-- Collapsible wrapper -->
      <div id="navbarRightAlignExample" class="collapse navbar-collapse">
        <!-- Left links -->
        <div
          class="navbar-nav ms-auto my-2 my-lg-0 navbar-nav-scroll"
          style="--bs-scroll-height: 100px"
        >
          <ul class="navbar-nav ms-auto my-2 my-lg-0 navbar-nav-scroll">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="/admin"
                >Home</a
              >
            </li>

            <li class="nav-item">
              <a class="nav-link" href="/admin/category">Category</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/admin/trash">Trash</a>
            </li>
          </ul>
          <div class="vr"></div>
          <div class="container">
            <button class="btn btn-outline-danger me-2" type="button">
              Log Out
            </button>
          </div>
        </div>

        <!-- Left links -->
      </div>
    </div>
  </nav>
</template>
