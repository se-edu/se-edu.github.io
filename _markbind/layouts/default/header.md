<header>
<navbar placement="top" type="dark">
  <a slot="brand" href="https://se-edu.github.io" title="SE-EDU Home" class="navbar-brand"> <md>:fas-home: ****SE-EDU****</md></a>
  <li><a href="{{baseUrl}}/docs/templates.html" class="nav-link"><md>**Project templates**</md></a></li>
  <li><a href="{{baseUrl}}/docs/resources.html" class="nav-link"><md>**Learning resources**</md></a></li>
  <li><a href="{{baseUrl}}/docs/tools.html" class="nav-link"><md>**Tools**</md></a></li>
  <li><a href="{{baseUrl}}/docs/team.html" class="nav-link"><md>**Team**</md></a></li>
  <li slot="right" class="nav-link">
    <form class="navbar-form">
      <searchbar :data="searchData" placeholder="Search this site" :on-hit="searchCallback" menu-align-right ></searchbar>
    </form>
  </li>
</navbar>
</header>
