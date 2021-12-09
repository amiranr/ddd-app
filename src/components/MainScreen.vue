<template>
  <div class="container bg-gray-400 text-center pt-2 pb-10  font-sans "> 
    <div class="h-20 bg-gray-500 mt-8 mr-3 ml-3 mb-8 rounded-md sm:w-48 shadow-md">Add banner </div>
    <div class="bg-gray-800 mt-8 mx-3 mb-4 rounded-sm shadow-md px-4 py-2 ">
      <div class="grid grid-cols-3">
        <div class=" py-1 ">
          <div class=" h-24 bg-gray-50 mt-2 mb-2 ml-1 mr-1  "> QR Code </div>
          <button class="bg-green-300 hover:bg-green-400 text-black text-sm px-1 py-1 rounded w-2/3" >Scan QR</button>
        </div>
        <div class=" col-span-2 mx-2 my-1  shadow-md">
          <div class="grid grid-cols-3 mb-2">
            <h1 class="ml-10 text-white text-xl font-bold "> #19 </h1>
            <div class="col-span-2 ">
              <p class="text-white">#18 ______ </p>
              <p class="text-white">#20 ______ </p>
            </div>
            
          </div> 
          <div class="bg-gray-400  mt-6 mb-1 ml-10  my-1 text-sm sm:text-lg ">Mission count:  </div>
          <div class="bg-gray-400  ml-10 my-1 mt-2 mb-1 text-sm sm:text-lg ">Current points: </div>
        </div>
        
      </div>
    </div>
    
    <div class="grid grid-cols-4 mx-2 my-2 px-1 py-2 ">
      
      <div class="bg-gray-500 h-32 mr-1 ">
        <p class=" text-opacity-80">Mission 1</p
        ></div>
      <div class="bg-gray-500 h-32 mr-1 ">
        <p class="text-opacity-95">Mission 2</p>
        </div>
      <div class="bg-gray-500 h-32 mr-1">Mission 3
        
      </div>
      <div class="bg-gray-500 h-32">Mission 4</div>

      </div>
    <div class="bg-gray-300 mt-1 mx-3 px-1 py-1 rounded-sm shadow-sm">
      <ul role="list" class="divide-y divide-gray-200">
        <li class="py-4 flex">
          <img class="h-10 w-10 rounded-full ml-4  " src="https://images.unsplash.com/photo-1491528323818-fdd1faba62cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80">
          <div class="ml-3">
            <p class="text-sm font-medium text-gray-900">Person 1</p>
            <p class="text-sm text-gray-500 ">Lorem Ipsum dolor sit amet, consectetur adipiscing elit.</p>
          </div>
        </li>
        <li class="py-4 flex">
          <img class="h-10 w-10 rounded-full ml-4" src="https://images.unsplash.com/photo-1550525811-e5869dd03032?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80">
          <div class="ml-3">
            <p class="text-sm font-medium text-gray-900">Person 2</p>
            <p class="text-sm text-gray-500">Lorem Ipsum dolor sit amet, consectetur adipiscing elit.</p>
          </div>
        </li>
        <li class="py-4 flex">
          <img class="h-10 w-10 rounded-full ml-4" src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80">
          <div class="ml-3">
            <p class="text-sm font-medium text-gray-900">Person 3</p>
            <p class="text-sm text-gray-500">Lorem Ipsum dolor sit amet, consectetur adipiscing elit.</p>
          </div>
        </li>
      </ul>
    </div>
    
      

    
    
  </div>
</template>

<script>
export default {
  name: 'MainScreen',
  
  props: {
    msg: String
  },
  
}
</script>

