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
            <div class="flex flex-wrap -mx-3 mb-20">

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

            <div class="flex flex-wrap -mx-3">

              <div class="w-full xl:w-1/3 px-3">
                <p class="text-xl font-semibold mb-4">Recent Sales</p>

                <div class="w-full bg-white border rounded-lg p-4 mb-8 xl:mb-0">
                  <canvas id="buyers-chart" width="600" height="400"></canvas>
                </div>
              </div>

              <div class="w-full xl:w-1/3 px-3">
                <p class="text-xl font-semibold mb-4">Recent Reviews</p>

                <div class="w-full bg-white border rounded-lg p-4 mb-8 xl:mb-0">
                  <canvas id="reviews-chart" width="600" height="400"></canvas>
                </div>
              </div>

              <div class="w-full xl:w-1/3 px-3">
                <p class="text-xl font-semibold mb-4">Recent Transactions</p>
                <div class="w-full bg-white border rounded-lg p-4">
                  <div class="w-full bg-gray-100 border rounded-lg flex justify-between items-center px-4 py-2 mb-4">
                      <div>
                          <p class="font-semibold text-xl">Trent Murphy</p>
                          <p>Product 1</p>
                      </div>
                      <span class="text-green-500 font-semibold text-lg">$25.00</span>
                  </div>

                  <div class="w-full bg-gray-100 border rounded-lg flex justify-between items-center px-4 py-2 mb-4">
                      <div>
                          <p class="font-semibold text-xl">Joseph Brent</p>
                          <p>Product 34</p>
                      </div>
                      <span class="text-red-500 font-semibold text-lg">$74.99</span>
                  </div>

                  <div class="w-full bg-gray-100 border rounded-lg flex justify-between items-center px-4 py-2 mb-4">
                      <div>
                          <p class="font-semibold text-xl">Jacob Bator</p>
                          <p>Product 23</p>
                      </div>
                      <span class="text-green-500 font-semibold text-lg">$14.95</span>
                  </div>

                  <div class="w-full bg-gray-100 border rounded-lg flex justify-between items-center px-4 py-2">
                      <div>
                          <p class="font-semibold text-xl">Alex Mason</p>
                          <p>Product 66</p>
                      </div>
                      <span class="text-green-500 font-semibold text-lg">$44.99</span>
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
                        backgroundColor : "rgba(99,179,237,0.4)",
                        strokeColor : "#63b3ed",
                        pointColor : "#fff",
                        pointStrokeColor : "#63b3ed",
                        data : [203,156,99,251,305,247,256]
                    },
                    {
                        backgroundColor : "rgba(198,198,198,0.4)",
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
                        backgroundColor : "rgba(99,179,237,0.4)",
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