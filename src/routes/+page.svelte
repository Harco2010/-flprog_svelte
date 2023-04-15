<script>
   
</script>

<main>
  <div class="flex flex-col h-screen bg-gray-50">
    <header class="h-10 w-full bg-gray-100 overflow-auto shadow-md">
        <div class="flex content-center items-center justify-end">
           <b class="flex justify-end text-center" />
        </div>
    </header>
    <nav class="flex">
        <input id="menu__toggle" type="checkbox" />
        <label class="menu__btn" for="menu__toggle">
          <span />
        </label>
        <ul class="menu__box">      
          <li>
            <a class="menu__item" href="/">{"Главная"}</a>
          </li>
          <li>
            <a class="menu__item" href="/config">{"Конфиг"}</a>
          </li>
          <li>
            <a class="menu__item" href="/connection">{"Подключение"}</a>
          </li>
        </ul>
        <ul class="menu__main ml-0">
           <div class="bg-cover pt-8 px-4">
              <div class="crd-grd-ln">
                <div class="crd">
                   <h1 class="crd-hdr">flprog_svelte</h1>
                </div> 
              </div>
           </div>
        </ul>
    </nav>
  </div>  
</main>


