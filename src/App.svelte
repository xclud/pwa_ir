<script>
  import avatar from "./assets/img/avatar.webp";
  import cover from "./assets/img/cover.webp";
  import Counter from "./lib/Counter.svelte";
</script>

<main class="main-container">
  <div class="grid gap-5 lg:grid-cols-3">
    <div class="space-y-5">
      <!-- Start Left Side -->

      <div class="shadow rounded-xl overflow-hidden">
        <!-- Start User Block -->
        <div
          class="h-32 bg-cover"
          style="background-image: url('{cover}');"
        />
        <div class="pt-14 p-7 bg-white relative">
          <img src="{avatar}" alt="Avatar" class="user-photo" />
          <div class="text-lg font-semibold mb-1.5">Mahdi K. Fard</div>
          <div class="text-sm text-gray-600 mb-1.5">Senior C# Developer</div>
          <div class="text-sm text-gray-500 mb-7">mkfard@outlook.com</div>
          
        <div class="flex flex-col space-y-4">
          <ul class="flex space-x-5">
            <li>
              <a
                aria-label="linkedin"
                href="https://linkedin.com/in/mkfard"
                target="_blank"
                class="social-link-hover"
              >
                <i class="bx bxl-linkedin text-2xl"></i>
              </a>
            </li>
            <li>
              <a
                aria-label="telegram"
                href="https://t.me/mahkfard"
                target="_blank"
                class="social-link-hover"
              >
                <i class="bx bxl-telegram text-2xl"></i>
              </a>
            </li>
            <li>
              <a
                aria-label="github"
                href="https://github.com/xclud"
                target="_blank"
                class="social-link-hover">
                <i class="bx bxl-github text-2xl"></i>
              </a>
            </li>
          </ul>
        </div>

        </div>
      </div>
      <!-- End User Block -->

      <div class="p-7 block-section">
        <!-- Start Info Block -->
        <h2 class="block-title">Information</h2>
        <div class="space-y-4">
          <div class="flex justify-between">
            <div class="text-gray-500">Location</div>
            <div class="font-medium text-right text-gray-600">Tehran</div>
          </div>
          <div class="flex justify-between">
            <div class="text-gray-500">Experience</div>
            <div class="font-medium text-right text-gray-600">20+ years</div>
          </div>
          <div class="flex justify-between">
            <div class="text-gray-500">Birth</div>
            <div class="font-medium text-right text-gray-600">1986</div>
          </div>
          <div class="flex justify-between">
            <div class="text-gray-500">Availability</div>
            <div class="font-medium text-right text-gray-600">Next Day</div>
          </div>
          <div class="flex justify-between">
            <div class="text-gray-500">Relocation</div>
            <div class="font-medium text-right text-gray-600">Yes</div>
          </div>
        </div>
      </div>
      <!-- End Info Block -->

      <div class="p-7 block-section flow-root">
        <!-- Start Skills Block -->
        <h2 class="block-title">Skills</h2>
        <div class="-m-2 flex flex-wrap">
          <span class="skill-tag">.NET 7.0</span>
          <span class="skill-tag">HTTP/3</span>
          <span class="skill-tag">gRPC</span>
          <span class="skill-tag">REST</span>
          <span class="skill-tag">NOSQL/SQL</span>
          <span class="skill-tag">Microservices</span>
        </div>
      </div>
      <!-- End Skills Block -->
    </div>
    <!-- End Left Side -->

    <div class="space-y-5 lg:col-span-2">
      <!-- Start Right Side -->

      <div class="p-7 pb-0 block-section">
        <!-- Start About Me Block -->
        <h2 class="block-title">About Me</h2>
        <p class="text-gray-600 mb-5">
          Hands-on software engineering manager, building and leading
          engineering teams with over 20 years of experience on .NET and C#.
        </p>

        <div class="border-t border-gray-200 my-5" />

        <ul class="flex space-x-8 font-medium">
          <li>
            <a href="/" class="menu-link-active menu-link-hover">Resume</a>
          </li>
          <li>
            <a href="/" class="menu-link menu-link-hover">Projects</a>
          </li>
        </ul>
      </div>
      <!-- End About Me Block -->

      <!--<div class="p-7 block-section">-->
      <!-- Start Interests Block -->
      <!--<h2 class="block-title">Interests</h2>
                    <div class="mb-5 item-section">
                        <div class="company-logo" style="background-color: #1DA1F2;">
                            <i class="bx bxl-twitter text-3xl"></i>
                        </div>

                        <div class="w-full space-y-5">
                            <div class="item-header">
                                <div class="space-y-1.5">
                                    <div class="font-medium">Developer Advocate</div>
                                    <div class="flex space-x-5">
                                        <div class="item-header-info">
                                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                                            </svg>
                                            <span>Freelance</span>
                                        </div>
                                        <div class="item-header-info">
                                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                                            </svg>
                                            <span>Tehran</span>
                                        </div>
                                    </div>
                                </div>
                                <div class="space-y-2 sm:text-right">
                                    <div class="job-item-badge">Remote</div>
                                    <div class="item-header-info">
                                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
                                        </svg>
                                        <span>September 2021 ??? Present</span>
                                    </div>
                                </div>
                            </div>
                            <p class="text-gray-600">
                                Giving advice to several tech companies and startups as a Developer Advocate. I introduce the technologies to the clients, make comparisons and present potential gain they would have migrating to the new technology. Then, I help them with implementation and i ease to the process by leading the whole transition.
                            </p>
                            <div class="border-b border-gray-200"></div>
                        </div>
                    </div>

                    <div class="mb-5 item-section">
                        <div class="company-logo" style="background-color: #0061FF;">
                            <i class="bx bxl-dropbox text-3xl"></i>
                        </div>

                        <div class="w-full space-y-5">
                            <div class="item-header">
                                <div class="space-y-1.5">
                                    <div class="font-medium">DevOps Architect</div>
                                    <div class="flex space-x-5">
                                        <div class="item-header-info">
                                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                                            </svg>
                                            <span>Eqtesad Novin Bank</span>
                                        </div>
                                        <div class="item-header-info">
                                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                                            </svg>
                                            <span>Tehran</span>
                                        </div>
                                    </div>
                                </div>
                                <div class="space-y-2 sm:text-right">
                                    <div class="job-item-badge">Full time</div>
                                    <div class="item-header-info">
                                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
                                        </svg>
                                        <span>August 2020 ??? September 2021</span>
                                    </div>
                                </div>
                            </div>
                            <p class="text-gray-600">
                                Working at the PSP (Payment Service Provider), my job was to design and architect a DevOps solution, and help the fellow developers with migrating the old .NET Framework projects to .NET 5.0 and then deploying them to the Kubernetes cluster.
                            </p>
                            <div class="border-b border-gray-200"></div>
                        </div>
                    </div>

                    <div class="item-section">
                        <div class="company-logo" style="background-color: #FC4F08;">
                            <i class="bx bxl-blogger text-3xl"></i>
                        </div>

                        <div class="w-full space-y-5">
                            <div class="item-header">
                                <div class="space-y-1.5">
                                    <div class="font-medium">Senior Developer</div>
                                    <div class="flex space-x-5">
                                        <div class="item-header-info">
                                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                                            </svg>
                                            <span>Iranian Space Research Center</span>
                                        </div>
                                        <div class="item-header-info">
                                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                                            </svg>
                                            <span>Tehran</span>
                                        </div>
                                    </div>
                                </div>
                                <div class="space-y-2 sm:text-right">
                                    <div class="job-item-badge">Full time</div>
                                    <div class="item-header-info">
                                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
                                        </svg>
                                        <span>March 2017 ??? March 2019</span>
                                    </div>
                                </div>
                            </div>
                            <p class="text-gray-600">
                                Details may not be disclosed.
                            </p>
                        </div>
                    </div>
                </div>-->
      <!-- End Interests Block -->

      <div class="p-7 block-section">        
        <!-- Start Experience Block -->
        <h2 class="block-title">Experience</h2>
        <div class="mb-5 item-section">
          <div class="w-full space-y-5">
            <div class="item-header">
              <div class="space-y-1.5">
                <div class="font-medium">Developer Advocate</div>
                <div class="flex space-x-5">
                  <div class="item-header-info">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-4 w-4"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                      />
                    </svg>
                    <span>Freelance</span>
                  </div>
                  <div class="item-header-info">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-4 w-4"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"
                      />
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"
                      />
                    </svg>
                    <span>Tehran</span>
                  </div>
                </div>
              </div>
              <div class="space-y-2 sm:text-right">
                <div class="job-item-badge">Remote</div>
                <div class="item-header-info">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-4 w-4"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
                    />
                  </svg>
                  <span>September 2021 ??? Present</span>
                </div>
              </div>
            </div>
            <p class="text-gray-600">
              Giving advice to several tech companies and startups as a
              Developer Advocate. I introduce the technologies to the clients,
              make comparisons and present potential gain they would have
              migrating to the new technology. Then, I help them with
              implementation and i ease to the process by leading the whole
              transition.
            </p>
            <div class="border-b border-gray-200" />
          </div>
        </div>

        <div class="mb-5 item-section">
          <div class="w-full space-y-5">
            <div class="item-header">
              <div class="space-y-1.5">
                <div class="font-medium">DevOps Architect</div>
                <div class="flex space-x-5">
                  <div class="item-header-info">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-4 w-4"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                      />
                    </svg>
                    <span>Eqtesad Novin Bank</span>
                  </div>
                  <div class="item-header-info">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-4 w-4"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"
                      />
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"
                      />
                    </svg>
                    <span>Tehran</span>
                  </div>
                </div>
              </div>
              <div class="space-y-2 sm:text-right">
                <div class="job-item-badge">Full time</div>
                <div class="item-header-info">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-4 w-4"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
                    />
                  </svg>
                  <span>August 2020 ??? September 2021</span>
                </div>
              </div>
            </div>
            <p class="text-gray-600">
              Working at the PSP (Payment Service Provider), my job was to
              design and architect a DevOps solution, and help the fellow
              developers with migrating the old .NET Framework projects to .NET
              5.0 and then deploying them to the Kubernetes cluster.
            </p>
            <div class="border-b border-gray-200" />
          </div>
        </div>

        <div class="item-section">
          <div class="w-full space-y-5">
            <div class="item-header">
              <div class="space-y-1.5">
                <div class="font-medium">Senior Developer</div>
                <div class="flex space-x-5">
                  <div class="item-header-info">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-4 w-4"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                      />
                    </svg>
                    <span>Iranian Space Research Center</span>
                  </div>
                  <div class="item-header-info">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-4 w-4"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"
                      />
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"
                      />
                    </svg>
                    <span>Tehran</span>
                  </div>
                </div>
              </div>
              <div class="space-y-2 sm:text-right">
                <div class="job-item-badge">Full time</div>
                <div class="item-header-info">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-4 w-4"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
                    />
                  </svg>
                  <span>March 2017 ??? March 2019</span>
                </div>
              </div>
            </div>
            <p class="text-gray-600">Details may not be disclosed online.</p>
          </div>
        </div>
      </div>
      <!-- Start Experience Block -->

      <div class="p-7 block-section">
        <!-- Start Education Block -->
        <h2 class="block-title">Education</h2>
        <div class="mb-5 item-section">
          <div class="w-full space-y-5">
            <div class="item-header items-end">
              <div class="space-y-1.5">
                <div class="font-medium">Master of Computer Science</div>
                <div class="flex space-x-5">
                  <div class="item-header-info">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-4 w-4"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path d="M12 14l9-5-9-5-9 5 9 5z" />
                      <path
                        d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14z"
                      />
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M12 14l9-5-9-5-9 5 9 5zm0 0l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14zm-4 6v-7.5l4-2.222"
                      />
                    </svg>
                    <span>Universidad Polit??cnica de Madrid</span>
                  </div>
                  <div class="item-header-info">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-4 w-4"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"
                      />
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"
                      />
                    </svg>
                    <span>Madrid</span>
                  </div>
                </div>
              </div>
              <div class="space-y-1.5 sm:text-right">
                <div class="item-header-info">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-4 w-4"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
                    />
                  </svg>
                  <span>September 2013 ??? September 2014</span>
                </div>
              </div>
            </div>
            <div class="border-b border-gray-200" />
          </div>
        </div>

        <div class="item-section">
          <div class="w-full space-y-5">
            <div class="item-header items-end">
              <div class="space-y-1.5">
                <div class="font-medium">Bachelor of Software Engineering</div>
                <div class="flex space-x-5">
                  <div class="item-header-info">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-4 w-4"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path d="M12 14l9-5-9-5-9 5 9 5z" />
                      <path
                        d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14z"
                      />
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M12 14l9-5-9-5-9 5 9 5zm0 0l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14zm-4 6v-7.5l4-2.222"
                      />
                    </svg>
                    <span>Azad University</span>
                  </div>
                  <div class="item-header-info">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-4 w-4"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"
                      />
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"
                      />
                    </svg>
                    <span>Yazd</span>
                  </div>
                </div>
              </div>
              <div class="space-y-1.5 sm:text-right">
                <div class="item-header-info">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-4 w-4"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
                    />
                  </svg>
                  <span>September 2004 ??? February 2009</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Start Education Block -->
    </div>
    <!-- End Right Side -->
  </div>
</main>
