<script setup>

</script>

<template>
  <main>
    <div class="container min-vh-100">
      <div class="row col-sm-12 col-md-12 col-lg-6 col-xxl-6 mx-auto">
        <div class="card boder border-0 mt-5">

          <div class="position-relative  mx-auto mt-5 border border-4 rounded rounded-circle">
            <img class=" border border-4 rounded rounded-circle" style="height: 200px;"
              src="https://alumni.engineering.utoronto.ca/files/2022/05/Avatar-Placeholder-400x400-1-300x300.jpg" alt=""
              srcset="">

            <label for="file-input"  class="position-absolute up-file text-light p-3 rounded rounded-circle"><i style="font-size: 20px;" class="fa-solid fa-cloud-arrow-up"></i></label>
          </div>

          <input hidden type="file" id="file-input" >


          <form class="p-5">
            <div class="mb-3">
              <label class="form-label" for="">Name</label>
              <input type="text" class="form-control">
            </div>

            <div class="mb-3">
              <label class="form-label" for="">Last Name</label>
              <input type="text" class="form-control">
            </div>

            <div class="mb-3">
              <label class="form-label" for="">Email</label>
              <input type="text" class="form-control">
            </div>

            <div class="mb-3">
              <label class="form-label" for="">Phone Number</label>
              <input type="text" class="form-control">
            </div>
      
            <div   class="mt-4 d-flex flex-column">
              <button disabled class="btn btn-dark" type="submit">Submit</button>
              <small>Fill de form to enable button!</small>
            </div>
          </form>
        </div>
      </div>
    </div>
  </main>
</template>
