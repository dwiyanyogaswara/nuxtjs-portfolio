<template>
  <div>
    <div class="container mx-auto">
      <main>
        <section id="home" class="mb-5 scroll-mt-20 h-screen">
          <div class="p-5">
            <div class="rounded-full overflow-hidden w-1/6 mx-auto">
              <img
                src="assets\images\linkedin.jpg"
                class="object-cover w-full h-full"
              />
            </div>
          </div>
          <div class="flex flex-col items-center">
            <div class="text-center text-2xl text-white">
              Hi, my name is Dwiyan Yogaswara. I am a software engineer based in
              Jakarta, Indonesia. I specialize in web and android application.
            </div>
            <div
              class="rounded-lg shadow-md p-3 mt-5 mb-5 w-3/5 bg-gradient-to-r from-blue-400 to-blue-900"
            >
              <div class="flex flex-row content-between">
                <div class="p-2 w-[200px] h-[200px] hover:animate-bounce">
                  <a
                    href="https://www.linkedin.com/in/dwiyan-yogaswara"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <img src="assets\images\linkedin-icon.png" alt=""
                  /></a>
                </div>
                <div class="p-2 w-[200px] h-[200px] hover:animate-bounce">
                  <a
                    href="https://wa.me/6285797736066"
                    target="_blank"
                    rel="noopener noreferrer"
                    ><img src="assets\images\whatsapp.png" alt=""
                  /></a>
                </div>
                <div class="p-2 w-[200px] h-[200px] hover:animate-bounce">
                  <a
                    href="https://github.com/dwiyanyogaswara"
                    target="_blank"
                    rel="noopener noreferrer"
                    ><img src="assets\images\github.png" alt=""
                  /></a>
                </div>
                <div class="p-2 w-[200px] h-[200px] hover:animate-bounce">
                  <a href="assets\files\CV 2023 Dwiyan Yogaswara.pdf" download
                    ><img src="assets\images\CV.png" alt=""
                  /></a>
                </div>
              </div>
            </div>
          </div>
        </section>
        <section id="skills" class="mb-8 scroll-mt-20">
          <h1 class="mb-4 text-2xl font-bold text-center tracking-widest">My Skills</h1>
          <div class="grid lg:grid-cols-3 gap-8">
            <div
              class="col-span-1 rounded-lg shadow-md p-6 mb-5 h-fit bg-gradient-to-r from-blue-400 to-blue-900 hover:from-indigo-400 hover:to-indigo-800"
            >
              <h3 class="mb-4 text-2xl font-bold text-center tracking-widest">Mobile</h3>
              <div class="grid grid-cols-1">
                <div class="p-2 mx-auto w-[200px] h-fit">
                  <img src="assets\images\flutter.png" alt="" />
                </div>
              </div>
            </div>
            <div
              class="col-span-2 rounded-lg shadow-md p-6 mb-5 h-fit bg-gradient-to-r from-blue-400 to-blue-900 hover:from-indigo-400 hover:to-indigo-800"
            >
              <h3 class="mb-4 text-2xl font-bold text-center tracking-widest">Frontend</h3>
              <div class="grid grid-cols-3">
                <div class="p-2 w-[200px] h-[200px]">
                  <img src="assets\images\vue.png" alt="" />
                </div>
                <div>
                  <div class="p-2 w-[200px] h-[100px]">
                    <img src="assets\images\nuxt.png" alt="" />
                  </div>
                  <div class="p-2 w-[200px] h-[100px]">
                    <img src="assets\images\bootstrap.png" alt="" />
                  </div>
                </div>
                <div class="p-2 w-[200px] h-[200px]">
                  <img src="assets\images\tailwind.png" alt="" />
                </div>
              </div>
            </div>
          </div>

          <div class="grid lg:grid-cols-2 gap-8">
            <div
              class="rounded-lg shadow-md p-6 mb-5 h-fit bg-gradient-to-r from-blue-400 to-blue-900 hover:from-indigo-400 hover:to-indigo-800"
            >
              <h3 class="mb-4 text-2xl font-bold text-center tracking-widest">Backend</h3>
              <div class="grid grid-cols-3">
                <div class="p-2">
                  <img src="assets\images\express.png" alt="" />
                </div>
                <div>
                  <div class="p-2">
                    <img src="assets\images\laravel.png" alt="" />
                  </div>
                  <div class="p-2">
                    <img src="assets\images\csharp.png" alt="" />
                  </div>
                </div>
                <div class="p-2">
                  <img src="assets\images\codeigniter.png" alt="aa" />
                </div>
              </div>
            </div>
            <div>
              <div
                class="rounded-lg shadow-md p-6 mb-5 bg-gradient-to-r from-blue-400 to-blue-900 hover:from-indigo-400 hover:to-indigo-800"
              >
                <h3 class="mb-4 text-2xl font-bold text-center tracking-widest">Database</h3>
                <div class="grid grid-cols-4">
                  <div class="p-2">
                    <img src="assets\images\mysql.png" alt="" />
                  </div>
                  <div>
                    <div class="p-2">
                      <img src="assets\images\postgresql.png" alt="" />
                    </div>
                    <div class="p-2">
                      <img src="assets\images\mongodb.png" alt="" />
                    </div>
                  </div>
                  <div class="p-2">
                    <img src="assets\images\mssql.png" alt="" />
                  </div>
                  <div class="p-2">
                    <img src="assets\images\oracle.png" alt="" />
                  </div>
                </div>
              </div>
              <div
                class="rounded-lg shadow-md p-6 mb-5 bg-gradient-to-r from-blue-400 to-blue-900 hover:from-indigo-400 hover:to-indigo-800"
              >
                <h3 class="mb-4 text-2xl font-bold text-center tracking-widest">Dev Ops</h3>
                <div class="grid grid-cols-1">
                  <div class="p-2 mx-auto">
                    <img src="assets\images\docker.png" alt="" />
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
        <section id="work" class="mb-8 scroll-mt-20 h-screen">
          <h1 class="mb-4 text-2xl font-bold text-center tracking-widest">Work Experience</h1>
          <div class="grid lg:grid-cols-2 gap-10 text-left">
            <div
              class="rounded-lg shadow-md p-6 mb-5 bg-gradient-to-r from-blue-400 to-blue-950 hover:from-indigo-400 hover:to-indigo-800"
            >
              <div class="text-center">Oct 2019 - Dec 2020</div>

              <div class="border-b-2 border-grey[600] my-2"></div>
              <div class="grid grid-cols-3 text-sm">
                <div class="col-span-1">
                  <div>Company</div>
                </div>
                <div class="col-span-2">
                  <div>: PT Jasamedika Saranatama</div>
                </div>
                <div class="col-span-1">
                  <div>Title</div>
                </div>
                <div class="col-span-2">
                  <div>: Programmer Site</div>
                </div>
                <div class="col-span-1">
                  <div>Job desc</div>
                </div>
                <div class="col-span-2">
                  <div>: Developed Management System for Hospital</div>
                </div>
                <div class="col-span-1">
                  <div>Technology</div>
                </div>
                <div class="col-span-2">
                  <div>: AngularJS, Laravel, MSSQL</div>
                </div>
              </div>
            </div>
            <div
              class="rounded-lg shadow-md p-6 mb-5 bg-gradient-to-r from-blue-400 to-blue-950 hover:from-indigo-400 hover:to-indigo-800"
            >
              <div class="text-center">Jan 2021 - Jun 2022</div>

              <div class="border-b-2 border-grey[600] my-2"></div>
              <div class="grid grid-cols-3 text-sm">
                <div class="col-span-1">
                  <div>Company</div>
                </div>
                <div class="col-span-2">
                  <div>: PT Visi Multimedia Aditama</div>
                </div>
                <div class="col-span-1">
                  <div>Title</div>
                </div>
                <div class="col-span-2">
                  <div>: API Dev</div>
                </div>
                <div class="col-span-1">
                  <div>Job desc</div>
                </div>
                <div class="col-span-2">
                  <div>: Developed API for rschooltoday.com</div>
                </div>
                <div class="col-span-1">
                  <div>Technology</div>
                </div>
                <div class="col-span-2">
                  <div>: Codeigniter, MySQL</div>
                </div>
              </div>
            </div>
            <div
              class="rounded-lg shadow-md p-6 mb-5 bg-gradient-to-r from-blue-400 to-blue-950 hover:from-indigo-400 hover:to-indigo-800"
            >
              <div class="text-center">Oct 2022 - Feb 2023</div>

              <div class="border-b-2 border-grey[600] my-2"></div>
              <div class="grid grid-cols-3 text-sm">
                <div class="col-span-1">
                  <div>Company</div>
                </div>
                <div class="col-span-2">
                  <div>: PT E-Property Batavianet</div>
                </div>
                <div class="col-span-1">
                  <div>Title</div>
                </div>
                <div class="col-span-2">
                  <div>: .NET Dev</div>
                </div>
                <div class="col-span-1">
                  <div>Job desc</div>
                </div>
                <div class="col-span-2">
                  <div>
                    : Developed Management System for Property Developer
                  </div>
                </div>
                <div class="col-span-1">
                  <div>Technology</div>
                </div>
                <div class="col-span-2">
                  <div>: C# .NET, MSSQL</div>
                </div>
              </div>
            </div>
            <div
              class="rounded-lg shadow-md p-6 mb-5 bg-gradient-to-r from-blue-400 to-blue-950 hover:from-indigo-400 hover:to-indigo-800"
            >
              <div class="text-center">Feb 2023 - Now</div>

              <div class="border-b-2 border-grey[600] my-2"></div>
              <div class="grid grid-cols-3 text-sm">
                <div class="col-span-1">
                  <div>Company</div>
                </div>
                <div class="col-span-2">
                  <div>: PT Indomarco Prismatama</div>
                </div>
                <div class="col-span-1">
                  <div>Title</div>
                </div>
                <div class="col-span-2">
                  <div>: .NET Dev</div>
                </div>
                <div class="col-span-1">
                  <div>Job desc</div>
                </div>
                <div class="col-span-2">
                  <div>
                    : Developed Distribution Center (DC) for retail company
                  </div>
                </div>
                <div class="col-span-1">
                  <div>Technology</div>
                </div>
                <div class="col-span-2">
                  <div>: VB .NET, Oracle</div>
                </div>
              </div>
            </div>
          </div>
        </section>
        <!-- <section id="portfolio" class="mb-8 scroll-mt-20">
          <h1 class="mb-4 text-2xl font-bold text-center">portfolio Section</h1>
        </section> -->
      </main>
    </div>
  </div>
</template>

<script setup>
</script>

<style scoped>
</style>