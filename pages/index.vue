<script setup lang="ts">

</script>

<template>
  <div class="row">
    <div class="col-md-4">
      <select class="form-select" aria-label="Default select example">
        <option selected>Selecting a genre</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
      </select>
    </div>
    <div class="col-md-4">
      <select class="form-select" aria-label="Default select example">
        <option selected>Country selection</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
      </select>
    </div>
    <div class="col-md-2">
      <select class="form-select" aria-label="Default select example">
        <option value="1">Name</option>
        <option value="2">Year</option>
        <option value="3">Rating</option>
      </select>
    </div>
    <div class="col-md-2">   <button type="button" class="btn btn-outline-info">Reset</button></div>
  </div>
  <div class="row row-cols-1 row-cols-md-3 g-4 mt-4">
    <div class="col">
      <div class="card">
        <img src="https://avatars.mds.yandex.net/get-kinopoisk-image/4774061/cf1970bc-3f08-4e0e-a095-2fb57c3aa7c6/600x900" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Матрица</h5>
          <p class="card-text">Мир Матрицы — это иллюзия, существующая только в бесконечном сне обреченного человечества. Холодный мир будущего, в котором люди — всего лишь батарейки в компьютерных системах.</p>
          <p class="card-text">110 мин.</p>
        </div>
      </div>
    </div>
    <div class="col">
    </div>
  </div>
  <div class="row row-cols-1 row-cols-md-3 g-4 mt-4">
    <div class="col">
      <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/ru/4/4d/Avengers_Infinity_War_poster.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Мстители: Война бесконечности</h5>
          <p class="card-text">Пока Мстители и их союзники продолжают защищать мир от различных опасностей, с которыми не смог бы справиться один супергерой, новая угроза возникает из космоса: Танос. Межгалактический тиран преследует цель собрать все шесть Камней Бесконечности — артефакты невероятной силы, с помощью которых можно менять реальность по своему желанию. Всё, с чем Мстители сталкивались ранее, вело к этому моменту — судьба Земли никогда ещё не была столь неопределённой.</p>
          <p class="card-text">190 мин.</p>
        </div>
      </div>
    </div>
    <div class="col">
    </div>
  </div>
  <nav aria-label="Page navigation example">
    <ul class="pagination">
      <li class="page-item">
        <a class="page-link" href="#" aria-label="Previous">
          <span aria-hidden="true">&laquo;</span>
        </a>
      </li>
      <li class="page-item"><a class="page-link" href="#">1</a></li>
      <li class="page-item"><a class="page-link" href="#">2</a></li>
      <li class="page-item"><a class="page-link" href="#">3</a></li>
      <li class="page-item">
        <a class="page-link" href="#" aria-label="Next">
          <span aria-hidden="true">&raquo;</span>
        </a>
      </li>
    </ul>
  </nav>
</template>