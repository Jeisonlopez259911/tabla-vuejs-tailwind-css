<script setup>

</script>

<template>
  <div class="border-collapse border-2 rounded-md">
    <div class="flex flex-col">
      <div class="overflow-x-auto sm:-mx-6 lg:-mx-8">
        <div class="inline-block min-w-full py-2 sm:px-6 lg:px-8">
          <div class="overflow-hidden">
            <table class="min-w-full text-left text-sm font-light text-surface dark:text-white">
              <thead class="border-b border-neutral-200 font-medium dark:border-white/10">
                <tr>
                  <th scope="col" class="whitespace-nowrap text-[#C7261E] cursor-pointer px-6 py-4"><v-icon name="fa-columns" /> COLUMNAS</th>
                  <th scope="col" class="whitespace-nowrap text-[#C7261E] cursor-pointer px-6 py-4"><v-icon name="fa-filter" /> FILTROS</th>
                  <th scope="col" class="whitespace-nowrap text-[#C7261E] cursor-pointer px-6 py-4"><v-icon name="fa-bars" /> DENSIDAD</th>
                  <th scope="col" class="whitespace-nowrap text-[#C7261E] cursor-pointer px-6 py-4"><v-icon name="fa-file-export" /> EXPORTAR</th>
                </tr>
                <tr>
                  <th scope="col" class="px-6 py-4">Carta porte</th>
                  <th scope="col" class="px-6 py-4">Transportadora</th>
                  <th scope="col" class="px-6 py-4">Estado</th>
                  <th scope="col" class="px-6 py-4">Cantidad</th>
                  <th scope="col" class="px-6 py-4">Precio total</th>
                  <th scope="col" class="px-6 py-4">Destino</th>
                </tr>
              </thead>
              <tbody>
                <tr class="border-b border-neutral-200 dark:border-white/10">
                  <td class="whitespace-nowrap px-6 py-4 font-medium">1</td>
                  <td class="whitespace-nowrap px-6 py-4">Mark</td>
                  <td class="whitespace-nowrap px-6 py-4">
                    <div class="rounded-full border-2 border-[#679E02] text-center text-[#679E02]">Liquidado</div>
                  </td>
                  <td class="whitespace-nowrap px-6 py-4">@mdo</td>
                  <td class="whitespace-nowrap px-6 py-4">Otto</td>
                  <td class="whitespace-nowrap px-6 py-4">@mdo</td>
                </tr>
                <tr class="border-b border-neutral-200 dark:border-white/10">
                  <td class="whitespace-nowrap px-6 py-4 font-medium">2</td>
                  <td class="whitespace-nowrap px-6 py-4">Jacob</td>
                  <td class="whitespace-nowrap px-6 py-4">
                    <div class="rounded-full border-2 border-[#F0AC00] text-center text-[#F0AC00]">Pendiente</div>
                  </td>
                  <td class="whitespace-nowrap px-6 py-4">@fat</td>
                  <td class="whitespace-nowrap px-6 py-4">Thornton</td>
                  <td class="whitespace-nowrap px-6 py-4">@fat</td>
                </tr>
                <tr class="border-b border-neutral-200 dark:border-white/10">
                  <td class="whitespace-nowrap px-6 py-4 font-medium">3</td>
                  <td class="whitespace-nowrap px-6 py-4">Larry</td>
                  <td class="whitespace-nowrap px-6 py-4">
                    <div class="rounded-full border-2 border-[#679E02] text-center text-[#679E02]">Liquidado</div>
                  </td>
                  <td class="whitespace-nowrap px-6 py-4">@twitter</td>
                  <td class="whitespace-nowrap px-6 py-4">Thornton</td>
                  <td class="whitespace-nowrap px-6 py-4">@fat</td>
                </tr>

              </tbody>
            </table>
          </div>
        </div>
      </div>
    </div>

    <div class="flex justify-end whitespace-nowrap">
      <div class="flex justify-end columns-2">
        <p>Filas por pagina: </p>
        <select name="" id="">
          <option value="">1</option>
          <option value="">2</option>
          <option value="">3</option>
        </select>
      </div>
      <nav aria-label="Page navigation example">
        <ul class="list-style-none flex">
          <li>
            <a
              class="pointer-events-none relative block rounded-full bg-transparent px-3 py-1.5 text-sm text-surface/50 transition duration-300 dark:text-neutral-400"><v-icon name="fa-angle-left" /></a>
          </li>
          <li>
            <a class="relative block rounded-full bg-transparent px-3 py-1.5 text-sm text-surface transition duration-300 hover:bg-neutral-100 focus:bg-neutral-100 focus:text-primary-700 focus:outline-none active:bg-neutral-100 active:text-primary-700 dark:text-white dark:hover:bg-neutral-700 dark:focus:bg-neutral-700  dark:focus:text-primary-500 dark:active:bg-neutral-700 dark:active:text-primary-500"
              href="#!">1</a>
          </li>
          <li aria-current="page">
            <a class="relative block rounded-full bg-primary-100 px-3 py-1.5 text-sm font-medium text-primary-700 transition duration-300 focus:outline-none dark:bg-slate-900 dark:text-primary-500"
              href="#!">2
              <span
                class="absolute -m-px h-px w-px overflow-hidden whitespace-nowrap border-0 p-0 [clip:rect(0,0,0,0)]">(current)</span>
            </a>
          </li>
          <li>
            <a class="relative block rounded-full bg-transparent px-3 py-1.5 text-sm text-surface transition duration-300 hover:bg-neutral-100 focus:bg-neutral-100 focus:text-primary-700 focus:outline-none active:bg-neutral-100 active:text-primary-700 dark:text-white dark:hover:bg-neutral-700 dark:focus:bg-neutral-700 dark:focus:text-primary-500 dark:active:bg-neutral-700 dark:active:text-primary-500"
              href="#!">3</a>
          </li>
          <li>
            <a class="relative block rounded-full bg-transparent px-3 py-1.5 text-sm text-surface transition duration-300 hover:bg-neutral-100 focus:bg-neutral-100 focus:text-primary-700 focus:outline-none active:bg-neutral-100 active:text-primary-700 dark:text-white dark:hover:bg-neutral-700 dark:focus:bg-neutral-700 dark:focus:text-primary-500 dark:active:bg-neutral-700 dark:active:text-primary-500"
              href="#!"><v-icon name="fa-angle-right" /></a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>