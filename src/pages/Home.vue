<template>
    <div id="home">

      <!-- breadcrumb -->
      <nav class="text-sm font-semibold mb-6" aria-label="Breadcrumb">
        <ol class="list-none p-0 inline-flex">
          <li class="flex items-center text-purple">
            <a href="/" class="text-gray-700">Home</a>
            <svg class="fill-current w-3 h-3 mx-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512"><path d="M285.476 272.971L91.132 467.314c-9.373 9.373-24.569 9.373-33.941 0l-22.667-22.667c-9.357-9.357-9.375-24.522-.04-33.901L188.505 256 34.484 101.255c-9.335-9.379-9.317-24.544.04-33.901l22.667-22.667c9.373-9.373 24.569-9.373 33.941 0L285.475 239.03c9.373 9.372 9.373 24.568.001 33.941z"/></svg>
          </li>
          <li class="flex items-center">
            <a href="/dashboard" class="text-gray-600">Dashboard</a>
          </li>
        </ol>
      </nav>
      <!-- breadcrumb end -->

      <div class="lg:flex justify-between items-center mb-6">
        <p class="text-2xl font-semibold mb-2 lg:mb-0 text-gray-800">Good afternoon, Joe!</p>
        <button class="bg-purple hover:bg-purple-light focus:outline-none rounded-lg px-6 py-2 text-white font-semibold shadow duration-150">View Logs</button>
      </div>

      <!-- Cards -->
      <div class="flex flex-wrap -mx-3 mb-16">

        <div class="w-1/2 xl:w-1/4 px-3">
          <div class="w-full bg-white border rounded-lg flex items-center p-0 mb-6 xl:mb-0">
            <div class="px-3 py-10 lg:px-5 lg:py-5 bg-pink text-white rounded-l-lg">
              <svg class="w-8 h-8 fill-current mx-auto hidden lg:block" viewBox="0 0 20 20">
                <path d="M17.35,2.219h-5.934c-0.115,0-0.225,0.045-0.307,0.128l-8.762,8.762c-0.171,0.168-0.171,0.443,0,0.611l5.933,5.934c0.167,0.171,0.443,0.169,0.612,0l8.762-8.763c0.083-0.083,0.128-0.192,0.128-0.307V2.651C17.781,2.414,17.587,2.219,17.35,2.219M16.916,8.405l-8.332,8.332l-5.321-5.321l8.333-8.332h5.32V8.405z M13.891,4.367c-0.957,0-1.729,0.772-1.729,1.729c0,0.957,0.771,1.729,1.729,1.729s1.729-0.772,1.729-1.729C15.619,5.14,14.848,4.367,13.891,4.367 M14.502,6.708c-0.326,0.326-0.896,0.326-1.223,0c-0.338-0.342-0.338-0.882,0-1.224c0.342-0.337,0.881-0.337,1.223,0C14.84,5.826,14.84,6.366,14.502,6.708"></path>
              </svg>
            </div>

            <div class="text-gray-700 ml-6 leading-6">
              <p class="font-semibold text-2xl">237</p>
              <p class="text-sm text-gray-600">Products Sold</p>
            </div>

          </div>
        </div>

        <div class="w-1/2 xl:w-1/4 px-3">
          <div class="w-full bg-white border rounded-lg flex items-center p-0 mb-6 xl:mb-0">
            <div class="px-3 py-10 lg:px-5 lg:py-5 bg-purple text-white rounded-l-lg">
              <svg class="w-8 h-8 fill-current mx-auto hidden lg:block" viewBox="0 0 20 20">
                <path d="M17.35,2.219h-5.934c-0.115,0-0.225,0.045-0.307,0.128l-8.762,8.762c-0.171,0.168-0.171,0.443,0,0.611l5.933,5.934c0.167,0.171,0.443,0.169,0.612,0l8.762-8.763c0.083-0.083,0.128-0.192,0.128-0.307V2.651C17.781,2.414,17.587,2.219,17.35,2.219M16.916,8.405l-8.332,8.332l-5.321-5.321l8.333-8.332h5.32V8.405z M13.891,4.367c-0.957,0-1.729,0.772-1.729,1.729c0,0.957,0.771,1.729,1.729,1.729s1.729-0.772,1.729-1.729C15.619,5.14,14.848,4.367,13.891,4.367 M14.502,6.708c-0.326,0.326-0.896,0.326-1.223,0c-0.338-0.342-0.338-0.882,0-1.224c0.342-0.337,0.881-0.337,1.223,0C14.84,5.826,14.84,6.366,14.502,6.708"></path>
              </svg>
            </div>

            <div class="text-gray-700 ml-6 leading-6">
              <p class="font-semibold text-2xl">42</p>
              <p class="text-sm text-gray-600">Products Sold</p>
            </div>

          </div>
        </div>

        <div class="w-1/2 xl:w-1/4 px-3">
          <div class="w-full bg-white border rounded-lg flex items-center p-0 mb-6 xl:mb-0">
            <div class="px-3 py-10 lg:px-5 lg:py-5 bg-orange text-white rounded-l-lg">
              <svg class="w-8 h-8 fill-current mx-auto hidden lg:block" viewBox="0 0 20 20">
                <path d="M17.35,2.219h-5.934c-0.115,0-0.225,0.045-0.307,0.128l-8.762,8.762c-0.171,0.168-0.171,0.443,0,0.611l5.933,5.934c0.167,0.171,0.443,0.169,0.612,0l8.762-8.763c0.083-0.083,0.128-0.192,0.128-0.307V2.651C17.781,2.414,17.587,2.219,17.35,2.219M16.916,8.405l-8.332,8.332l-5.321-5.321l8.333-8.332h5.32V8.405z M13.891,4.367c-0.957,0-1.729,0.772-1.729,1.729c0,0.957,0.771,1.729,1.729,1.729s1.729-0.772,1.729-1.729C15.619,5.14,14.848,4.367,13.891,4.367 M14.502,6.708c-0.326,0.326-0.896,0.326-1.223,0c-0.338-0.342-0.338-0.882,0-1.224c0.342-0.337,0.881-0.337,1.223,0C14.84,5.826,14.84,6.366,14.502,6.708"></path>
              </svg>
            </div>

            <div class="text-gray-700 ml-6 leading-6">
              <p class="font-semibold text-2xl">5</p>
              <p class="text-sm text-gray-600">Products Sold</p>
            </div>

          </div>
        </div>

        <div class="w-1/2 xl:w-1/4 px-3">
          <div class="w-full bg-white border rounded-lg flex items-center p-0 mb-6 xl:mb-0">
            <div class="px-3 py-10 lg:px-5 lg:py-5 bg-green text-white rounded-l-lg">
              <svg class="w-8 h-8 fill-current mx-auto hidden lg:block" viewBox="0 0 20 20">
                <path d="M17.35,2.219h-5.934c-0.115,0-0.225,0.045-0.307,0.128l-8.762,8.762c-0.171,0.168-0.171,0.443,0,0.611l5.933,5.934c0.167,0.171,0.443,0.169,0.612,0l8.762-8.763c0.083-0.083,0.128-0.192,0.128-0.307V2.651C17.781,2.414,17.587,2.219,17.35,2.219M16.916,8.405l-8.332,8.332l-5.321-5.321l8.333-8.332h5.32V8.405z M13.891,4.367c-0.957,0-1.729,0.772-1.729,1.729c0,0.957,0.771,1.729,1.729,1.729s1.729-0.772,1.729-1.729C15.619,5.14,14.848,4.367,13.891,4.367 M14.502,6.708c-0.326,0.326-0.896,0.326-1.223,0c-0.338-0.342-0.338-0.882,0-1.224c0.342-0.337,0.881-0.337,1.223,0C14.84,5.826,14.84,6.366,14.502,6.708"></path>
              </svg>
            </div>

            <div class="text-gray-700 ml-6 leading-6">
              <p class="font-semibold text-2xl">1,906</p>
              <p class="text-sm text-gray-600">Products Sold</p>
            </div>

          </div>
        </div>

      </div>

      <!-- table -->
      <div class="flex flex-col mb-12 bg-gray-25 rounded-md border border-gray-300">
        <div class="-my-2 overflow-x-auto sm:-mx-6 lg:-mx-8">
          <div class="py-2 align-middle inline-block min-w-full sm:px-6 lg:px-8">
            <div class="overflow-hidden sm:rounded-lg">
              <table class="min-w-full divide-y divide-gray-200">
                <thead>
                  <tr>
                    <th class="px-6 py-3 bg-gray-50 text-left text-xs leading-4 font-medium text-gray-700 uppercase tracking-wider">
                      Name
                    </th>
                    <th class="px-6 py-3 bg-gray-50 text-left text-xs leading-4 font-medium text-gray-700 uppercase tracking-wider">
                      Title
                    </th>
                    <th class="px-6 py-3 bg-gray-50 text-left text-xs leading-4 font-medium text-gray-700 uppercase tracking-wider">
                      Status
                    </th>
                    <th class="px-6 py-3 bg-gray-50 text-left text-xs leading-4 font-medium text-gray-700 uppercase tracking-wider">
                      Team
                    </th>
                    <th class="px-6 py-3 bg-gray-50"></th>
                  </tr>
                </thead>
                <tbody class="bg-white divide-y divide-gray-200 border-t border-gray-300">
                  <tr class="border-b border-gray-200">
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <div class="flex items-center">
                        <div class="h-3 w-3 mr-2 rounded-full bg-green"></div>
                        <div class="ml-4">
                          <div class="text-sm leading-5 font-medium text-gray-900">
                            Jane Cooper
                          </div>
                          <div class="text-sm leading-5 text-gray-500">
                            jane.cooper@example.com
                          </div>
                        </div>
                      </div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <div class="text-sm leading-5 text-gray-900">Regional Paradigm Technician</div>
                      <div class="text-sm leading-5 text-gray-500">Optimization</div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-200 text-green-700">
                        Active
                      </span>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500">
                      <div class="flex overflow-hidden">
                        <img class="inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/flagged/photo-1565257669119-6af359b65ea2?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/photo-1542909168-6296a31d7689?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/flagged/photo-1579500647742-5f34826ec327?ixlib=rb-1.2.1&auto=format&fit=crop&w=676&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/photo-1571175351749-e8d06f275d85?ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=80" alt="">
                        <span class="my-auto ml-2 text-xs font-semibold text-gray-500">+8</span>
                      </div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap text-right text-sm leading-5 font-medium">
                      <a href="#" class="text-purple .hover:bg-purple-light duration-150">Editar</a>
                    </td>
                  </tr>
                  <tr class="border-b border-gray-200">
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <div class="flex items-center">
                        <div class="h-3 w-3 mr-4 rounded-full bg-purple"></div>
                        <div class="ml-4">
                          <div class="text-sm leading-5 font-medium text-gray-900">
                            Jane Cooper
                          </div>
                          <div class="text-sm leading-5 text-gray-500">
                            jane.cooper@example.com
                          </div>
                        </div>
                      </div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <div class="text-sm leading-5 text-gray-900">Regional Paradigm Technician</div>
                      <div class="text-sm leading-5 text-gray-500">Optimization</div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-200 text-green-700">
                        Active
                      </span>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500">
                      <div class="flex overflow-hidden">
                        <img class="inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/flagged/photo-1565257669119-6af359b65ea2?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/photo-1542909168-6296a31d7689?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/flagged/photo-1579500647742-5f34826ec327?ixlib=rb-1.2.1&auto=format&fit=crop&w=676&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/photo-1571175351749-e8d06f275d85?ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=80" alt="">
                        <span class="my-auto ml-2 text-xs font-semibold text-gray-500">+3</span>
                      </div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap text-right text-sm leading-5 font-medium">
                      <a href="#" class="text-purple .hover:bg-purple-light duration-150">Editar</a>
                    </td>
                  </tr>
                  <tr class="border-b border-gray-200">
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <div class="flex items-center">
                        <div class="h-3 w-3 mr-4 rounded-full bg-orange"></div>
                        <div class="ml-4">
                          <div class="text-sm leading-5 font-medium text-gray-900">
                            Jane Cooper
                          </div>
                          <div class="text-sm leading-5 text-gray-500">
                            jane.cooper@example.com
                          </div>
                        </div>
                      </div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <div class="text-sm leading-5 text-gray-900">Regional Paradigm Technician</div>
                      <div class="text-sm leading-5 text-gray-500">Optimization</div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-200 text-green-700">
                        Active
                      </span>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500">
                      <div class="flex overflow-hidden">
                        <img class="inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/flagged/photo-1565257669119-6af359b65ea2?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/photo-1542909168-6296a31d7689?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/photo-1571175351749-e8d06f275d85?ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=80" alt="">
                      </div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap text-right text-sm leading-5 font-medium">
                      <a href="#" class="text-purple .hover:bg-purple-light duration-150">Editar</a>
                    </td>
                  </tr>
                  <tr class="border-b border-gray-200">
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <div class="flex items-center">
                        <div class="h-3 w-3 mr-4 rounded-full bg-pink"></div>
                        <div class="ml-4">
                          <div class="text-sm leading-5 font-medium text-gray-900">
                            Jane Cooper
                          </div>
                          <div class="text-sm leading-5 text-gray-500">
                            jane.cooper@example.com
                          </div>
                        </div>
                      </div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <div class="text-sm leading-5 text-gray-900">Regional Paradigm Technician</div>
                      <div class="text-sm leading-5 text-gray-500">Optimization</div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-200 text-green-700">
                        Active
                      </span>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500">
                      <div class="flex overflow-hidden">
                        <img class="inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/flagged/photo-1565257669119-6af359b65ea2?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/photo-1542909168-6296a31d7689?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/flagged/photo-1579500647742-5f34826ec327?ixlib=rb-1.2.1&auto=format&fit=crop&w=676&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/photo-1571175351749-e8d06f275d85?ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=80" alt="">
                        <span class="my-auto ml-2 text-xs font-semibold text-gray-500">+12</span>
                      </div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap text-right text-sm leading-5 font-medium">
                      <a href="#" class="text-purple .hover:bg-purple-light duration-150">Editar</a>
                    </td>
                  </tr>
                  <tr class="border-b border-gray-200">
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <div class="flex items-center">
                        <div class="h-3 w-3 mr-4 rounded-full bg-purple"></div>
                        <div class="ml-4">
                          <div class="text-sm leading-5 font-medium text-gray-900">
                            Jane Cooper
                          </div>
                          <div class="text-sm leading-5 text-gray-500">
                            jane.cooper@example.com
                          </div>
                        </div>
                      </div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <div class="text-sm leading-5 text-gray-900">Regional Paradigm Technician</div>
                      <div class="text-sm leading-5 text-gray-500">Optimization</div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-200 text-green-700">
                        Active
                      </span>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500">
                      <div class="flex overflow-hidden">
                        <img class="inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/flagged/photo-1565257669119-6af359b65ea2?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/photo-1542909168-6296a31d7689?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" alt="">
                      </div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap text-right text-sm leading-5 font-medium">
                      <a href="#" class="text-purple .hover:bg-purple-light duration-150">Editar</a>
                    </td>
                  </tr>
                  <tr class="border-b border-gray-200">
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <div class="flex items-center">
                        <div class="h-3 w-3 mr-4 rounded-full bg-orange"></div>
                        <div class="ml-4">
                          <div class="text-sm leading-5 font-medium text-gray-900">
                            Jane Cooper
                          </div>
                          <div class="text-sm leading-5 text-gray-500">
                            jane.cooper@example.com
                          </div>
                        </div>
                      </div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <div class="text-sm leading-5 text-gray-900">Regional Paradigm Technician</div>
                      <div class="text-sm leading-5 text-gray-500">Optimization</div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap">
                      <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-200 text-green-700">
                        Active
                      </span>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500">
                      <div class="flex overflow-hidden">
                        <img class="inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/flagged/photo-1565257669119-6af359b65ea2?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/photo-1542909168-6296a31d7689?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/flagged/photo-1579500647742-5f34826ec327?ixlib=rb-1.2.1&auto=format&fit=crop&w=676&q=80" alt="">
                        <img class="-ml-1 inline-block h-8 w-8 rounded-full text-white shadow-solid" src="https://images.unsplash.com/photo-1571175351749-e8d06f275d85?ixlib=rb-1.2.1&auto=format&fit=crop&w=700&q=80" alt="">
                        <span class="my-auto ml-2 text-xs font-semibold text-gray-500">+3</span>
                      </div>
                    </td>
                    <td class="px-6 py-4 whitespace-no-wrap text-right text-sm leading-5 font-medium">
                      <a href="#" class="text-purple .hover:bg-purple-light duration-150">Editar</a>
                    </td>
                  </tr>
                  <!-- More rows... -->
                </tbody>
              </table>
            </div>
          </div>
        </div>
      </div>

      <!-- charts -->
      <div class="flex flex-wrap -mx-3">

        <div class="w-full xl:w-1/3 px-3">
          <p class="text-xl font-semibold mb-4 text-gray-700">Recent Sales</p>

          <div class="w-full bg-white border rounded-lg p-4 mb-8 xl:mb-0">
            <canvas id="buyers-chart" width="600" height="400"></canvas>
          </div>
        </div>

        <div class="w-full xl:w-1/3 px-3">
          <p class="text-xl font-semibold mb-4 text-gray-700">Recent Reviews</p>

          <div class="w-full bg-white border rounded-lg p-4 mb-8 xl:mb-0">
            <canvas id="reviews-chart" width="600" height="400"></canvas>
          </div>
        </div>

        <div class="w-full xl:w-1/3 px-3">
          <p class="text-xl font-semibold mb-4 text-gray-700">Recent Transactions</p>
          <div class="w-full bg-white border rounded-lg p-4">
            
            <div class="w-full bg-gray-100 border rounded-lg flex justify-between items-center px-4 py-2 mb-4">
                <div>
                    <p class="font-semibold text-base text-gray-700">Jhon Doe</p>
                    <p class="text-sm text-gray-700">Product XYZ-92</p>
                </div>
                <span class="text-green-600 font-semibold text-lg">$25.00</span>
            </div>

            <div class="w-full bg-gray-100 border rounded-lg flex justify-between items-center px-4 py-2 mb-4">
                <div>
                    <p class="font-semibold text-base text-gray-700">Malcom</p>
                    <p class="text-sm text-gray-700">Product XYZ-92</p>
                </div>
                <span class="text-pink font-semibold text-lg">$74.99</span>
            </div>

            <div class="w-full bg-gray-100 border rounded-lg flex justify-between items-center px-4 py-2 mb-4">
                <div>
                    <p class="font-semibold text-base text-gray-700">Jhon Doe</p>
                    <p class="text-sm text-gray-700">Product XYZ-92</p>
                </div>
                <span class="text-green-600 font-semibold text-lg">$182.00</span>
            </div>

          </div>
        </div>

      </div>

    </div>
</template>

<script>
import Chart from 'chart.js'

export default {
    name: 'DashboardHome',
    data() {
        return {
            buyersData: {
                type: 'line',
                data: {
                    labels : ["Mon","Tue","Wed","Thu","Fri","Sat","Sun"],
                    datasets:[{
                        backgroundColor : "rgba(70,20,237,0.4)",
                        strokeColor : "#63b3ed",
                        pointColor : "#fff",
                        pointStrokeColor : "#63b3ed",
                        data : [203,156,99,251,305,247,256]
                    },
                    {
                        backgroundColor : "rgba(60,60,248,0.4)",
                        strokeColor : "#f7fafc",
                        pointColor : "#fff",
                        pointStrokeColor : "#f7fafc",
                        data : [86,97,144,114,94,108,156]
                    }]
                },
                options: {
                    legend: {
                        display: false
                    },
                    scales: {
                        yAxes: [{
                            gridLines: {
                                display:false
                            },  
                            ticks: {
                                display: false
                            }
                        }],
                        xAxes: [{
                            gridLines: {
                                display: false
                            }
                        }]
                    }
                }
            },
            reviewsData: {
                type: 'bar',
                data: {
                    labels : ["Mon","Tue","Wed","Thu","Fri","Sat","Sun"],
                    datasets:[{
                        backgroundColor : "rgba(40,100,255,0.8)",
                        strokeColor : "#63b3ed",
                        pointColor : "#fff",
                        pointStrokeColor : "#63b3ed",
                        data : [203,156,99,251,305,247,256]
                    }]
                },
                options: {
                    legend: {
                        display: false
                    },
                    scales: {
                        yAxes: [{
                            gridLines: {
                                display:false
                            },  
                            ticks: {
                                display: false
                            }
                        }],
                        xAxes: [{
                            gridLines: {
                                display: false
                            }
                        }]
                    }
                }

            }
        }
    },
    mounted () {
        new Chart(document.getElementById('buyers-chart'), this.buyersData)
        new Chart(document.getElementById('reviews-chart'), this.reviewsData)
    }
}
</script>