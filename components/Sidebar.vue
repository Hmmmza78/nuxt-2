<template>
    <div>
        
      <div
        class="d-flex flex-column flex-shrink-0 p-3 bg-light"
        style="width: 280px"
      >
        <a
          href="/"
          class="d-flex align-items-center mb-3 mb-md-0 me-md-auto link-dark text-decoration-none"
        >
          <svg class="bi me-2" width="40" height="32">
            <use xlink:href="#bootstrap"></use>
          </svg>
          <span class="fs-4">Sidebar</span><i class="fa-light fa-ellipsis-stroke"></i><font-awesome-icon icon="fa-sharp fa-solid fa-hand-dots" />
        </a>
        <hr />
        <ul class="nav nav-pills flex-column mb-auto">
          <li class="nav-item">
            <a href="#" class="nav-link active" aria-current="page">
              <svg class="bi me-2" width="16" height="16">
                <use xlink:href="#home"></use>
              </svg>
              Home<i class="fa-light fa-ellipsis-stroke"></i>
            </a>
          </li>
          <li>
            <a href="#" class="nav-link link-dark">
              <svg class="bi me-2" width="16" height="16">
                <use xlink:href="#speedometer2"></use>
              </svg>
              Dashboard
            </a>
          </li>
          <li>
            <a href="#" class="nav-link link-dark">
              <svg class="bi me-2" width="16" height="16">
                <use xlink:href="#table"></use>
              </svg>
              Orders
            </a>
          </li>
          <li>
            <a href="#" class="nav-link link-dark">
              <svg class="bi me-2" width="16" height="16">
                <use xlink:href="#grid"></use>
              </svg>
              Products
            </a>
          </li>
          <li>
            <a href="#" class="nav-link link-dark">
              <svg class="bi me-2" width="16" height="16">
                <use xlink:href="#people-circle"></use>
              </svg>
              Customers
            </a>
          </li>
        </ul>
        <hr />
      </div>
    </div>
</template>