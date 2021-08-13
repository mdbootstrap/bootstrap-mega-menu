# Bootstrap Mega Menu

Responsive Mega Menu built with Bootstrap 5. Examples of dropdown on click and on hover. Templates with grid, images, links, lists and more.

To learn more read [Navbar Docs](https://mdbootstrap.com/docs/standard/navigation/navbar/).

## Basic example

```html
<nav
  class="navbar navbar-expand-lg navbar-light bg-light"
>
  <!-- Container wrapper -->
  <div class="container-fluid">
    <!-- Toggle button -->
    <button
      class="navbar-toggler px-0"
      type="button"
      data-mdb-toggle="collapse"
      data-mdb-target="#navbarExample1"
      aria-controls="navbarExample1"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <i class="fas fa-bars"></i>
    </button>

    <!-- Collapsible wrapper -->
    <div
      class="collapse navbar-collapse"
      id="navbarExample1"
    >
      <!-- Left links -->
      <ul
        class="navbar-nav me-auto ps-lg-0"
        style="padding-left: 0.15rem"
      >
        <li class="nav-item">
          <a class="nav-link" href="#">Regular link</a>
        </li>
        <!-- Navbar dropdown -->
        <li class="nav-item dropdown position-static">
          <a
            class="nav-link dropdown-toggle"
            href="#"
            id="navbarDropdown"
            role="button"
            data-mdb-toggle="dropdown"
            aria-expanded="false"
          >
            Mega menu
          </a>
          <!-- Dropdown menu -->
          <div
            class="dropdown-menu w-100 mt-0"
            aria-labelledby="navbarDropdown"
            style="
              border-top-left-radius: 0;
              border-top-right-radius: 0;
            "
          >
            <div class="container">
              <div class="row my-4">
                <div
                  class="col-md-6 col-lg-3 mb-3 mb-lg-0"
                >
                  <div
                    class="list-group list-group-flush"
                  >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Lorem ipsum</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Dolor sit</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Amet consectetur</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Cras justo odio</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Adipisicing elit</a
                    >
                  </div>
                </div>
                <div
                  class="col-md-6 col-lg-3 mb-3 mb-lg-0"
                >
                  <div
                    class="list-group list-group-flush"
                  >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Explicabo voluptas</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Perspiciatis quo</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Cras justo odio</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Laudantium maiores</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Provident dolor</a
                    >
                  </div>
                </div>
                <div
                  class="col-md-6 col-lg-3 mb-3 mb-md-0"
                >
                  <div
                    class="list-group list-group-flush"
                  >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Iste quaerato</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Cras justo odio</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Est iure</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Praesentium</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Laboriosam</a
                    >
                  </div>
                </div>
                <div class="col-md-6 col-lg-3">
                  <div
                    class="list-group list-group-flush"
                  >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Cras justo odio</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Saepe</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Vel alias</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Sunt doloribus</a
                    >
                    <a
                      href=""
                      class="list-group-item list-group-item-action"
                      >Cum dolores</a
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
        </li>
      </ul>
      <!-- Left links -->
    </div>
    <!-- Collapsible wrapper -->
  </div>
  <!-- Container wrapper -->
</nav>
```

#### Much more examples and a detailed description can be found at [📄 Mega Menu documentation page](https://mdbootstrap.com/docs/standard/extended/mega-menu/)
