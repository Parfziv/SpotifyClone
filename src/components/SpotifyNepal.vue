<template>
  <div>
    <div class="flex flex-col h-screen text-sm text-gray-400">
      <div class="flex-1 flex overflow-y-hidden">
        <div class="bg-sidebar font-semibold font-sujan flex-none w-48 overflow-y-auto flex flex-col justify-between">
          <ul class="py-6">
            <li class=" border-green-500  border-l-4">
              <a href="#" class="flex items-center mx-4 mt-4 group">
                <svg class="w-6 h-6 group-hover:text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"/></svg>
                <span class="ml-2 group-hover:text-white">Home</span>
              </a>
            </li>
            <li class="border-l-4 border-transparent">
              <a href="#" class="flex items-center mx-4 mt-4 group">
                <svg class="w-6 h-6 group-hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z" clip-rule="evenodd"/></svg>
                <span class="ml-2 group-hover:text-white">Browse</span>
              </a>
            </li>
            <li class="border-l-4 border-transparent">
              <a href="#" class="flex items-center mx-4 mt-4 group">
                <svg class="w-6 h-6 group-hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M2 5a2 2 0 012-2h8a2 2 0 012 2v10a2 2 0 002 2H4a2 2 0 01-2-2V5zm3 1h6v4H5V6zm6 6H5v2h6v-2z" clip-rule="evenodd"/><path d="M15 7h1a2 2 0 012 2v5.5a1.5 1.5 0 01-3 0V7z"/></svg>
                <span class="ml-2 group-hover:text-white">Radio</span>
              </a>
            </li>
          </ul>
          <div class="overflow-y-auto px-4 mt-2 sidebar-spotify">
            <h3 class="uppercase tracking-widest text-gray-500 font-normal mb-2">Your Library</h3>
            <ul class="leading-loose">
              <li class="truncate"><a href="#" class="hover:text-white">Made For You</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Recently Played</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Liked Songs</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Albums</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Artists</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Podcasts</a></li>
            </ul>
              <h3 class="uppercase tracking-widest text-gray-500 font-normal  mt-6 mb-2">Playlists</h3>
          <ul class="leading-loose mb-6">
            <li class="truncate"><a href="#" class="hover:text-white">Acoustic Hits</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Acoustic Covers</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Discover Weekly</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Hot Hits Canada</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">90's Hip-Hop Don't Stop Long Text</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">90s Smash Hits</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">TGIF</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">mint Canada</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Hip-Hop Central</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">R&amp;B Right Now</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">I Love My '90s R&amp;B</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Are &amp; Be</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Today's Top Hits</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Get Turnt</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">iTunes</a></li>
          </ul>
          </div>
          <div class="py-4 h-16 border-gray-800 border-t-2">
            <a href="#" class="flex items-center group px-4">
            <svg class="w-6 h-6 text-gray-500 group-hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-11a1 1 0 10-2 0v2H7a1 1 0 100 2h2v2a1 1 0 102 0v-2h2a1 1 0 100-2h-2V7z" clip-rule="evenodd"></path></svg>
            <span class="ml-2 text-gray-500 group-hover:text-white">New Playlist</span>
            </a>
          </div>
        </div>
        <div class="flex-1  bg-content flex flex-col">
          <div class="flex items-center justify-between">
            <div class="flex items-center px-4 py-2">
              <button>
                <svg class="w-6 h-6 text-gray-400 hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M12.707 5.293a1 1 0 010 1.414L9.414 10l3.293 3.293a1 1 0 01-1.414 1.414l-4-4a1 1 0 010-1.414l4-4a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
              </button>
              <button class="ml-2">
                <svg class="w-6 h-6 hover:text-white text-gray-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd"></path></svg>
              </button>
              <div class="relative ml-4">
                <input type="text" placeholder="Search" class="py-1 rounded-full placeholder-gray-400 px-2 ml-2 pl-8">
                <div class="absolute top-0">
                  <svg class="w-6 h-6 pl-2 pt-1 ml-2 text-gray-400 hover:text-gray-800" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z" clip-rule="evenodd"></path></svg>
                </div>
              </div>
            </div>
            <div class="flex items-center px-4 py-2">
              <button><svg class="w-6 h-6 text-gray-400 hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-6-3a2 2 0 11-4 0 2 2 0 014 0zm-2 4a5 5 0 00-4.546 2.916A5.986 5.986 0 0010 16a5.986 5.986 0 004.546-2.084A5 5 0 0010 11z" clip-rule="evenodd"></path></svg></button>
               <a href="#" class="ml-4 hover:underline hover:text-white font-sujan">Sudan Ghimire</a>
               <button class="ml-6">
                 <svg class="w-6 h-6 text-gray-400 hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
               </button>             
            </div>
          </div>
          <div class="content-spotify overflow-y-auto">
            <div class="container px-32 mb-8">
            <h2 class="mt-24 text-5xl font-semibold text-white">Home</h2>
            <div class="mt-12">
              <h3 class="font-semibold text-xl border-b border-gray-700 pb-2">Recently Played</h3>
            </div>
            <div class="flex items-center mt-4 -mx-4">
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
            </div>
            <div class="mt-12">
              <h3 class="font-semibold text-xl border-b border-gray-700 pb-2">Recently Played</h3>
            </div>
            <div class="flex items-center mt-4 -mx-4">
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
            </div>
            <div class="mt-12">
              <h3 class="font-semibold text-xl border-b border-gray-700 pb-2">Recently Played</h3>
            </div>
            <div class="flex items-center mt-4 -mx-4">
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
                <div class="w-1/5 px-4">
                  <div>
                    <a href="#"><img src="https://images.unsplash.com/photo-1575756985239-ad4f602904d3?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8MTJ8fG11c2ljJTIwYXJ0aXN0fGVufDB8fDB8&auto=format&fit=crop&w=500&q=60" alt="album cover" class="h-32 w-32 object-cover"></a>
                  </div>
                  <div>
                    <a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a>
                    <div class="text-gray-500 mt-2">Amazing Acoustic Covers updated every week.</div>
                    <div class="uppercase tracking-widest text-xs text-gray-500 mt-2">6679 Followers</div>
                  </div>
                </div>
            </div>


            </div>
          </div>

        </div>
      </div>
      <div class="bg-footer flex-none h-20 flex items-center justify-between">
        <div class="flex items-center px-6">
          <a href="#"><img src="https://images.unsplash.com/photo-1596125099843-4c28a6287ddb?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8M3x8YWxidW0lMjBhcnR8ZW58MHx8MHw%3D&auto=format&fit=crop&w=500&q=60" alt="album art" class="h-14 w-14 object-cover"></a>
          <div class="ml-3">
            <div><a href="#" class="text-gray-500 hover:text-white hover:underline">Skinny Love</a></div>
            <div><a href="#" class="text-gray-500 text-xs hover:text-white hover:underline">Bon Iver</a></div>
          </div>
        </div>
        <div class="flex flex-col justify-center">
          <div class="flex justify-center">
          <button><svg class="w-6 h-6 text-gray-500 hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M5 4a1 1 0 00-2 0v7.268a2 2 0 000 3.464V16a1 1 0 102 0v-1.268a2 2 0 000-3.464V4zM11 4a1 1 0 10-2 0v1.268a2 2 0 000 3.464V16a1 1 0 102 0V8.732a2 2 0 000-3.464V4zM16 3a1 1 0 011 1v7.268a2 2 0 010 3.464V16a1 1 0 11-2 0v-1.268a2 2 0 010-3.464V4a1 1 0 011-1z"></path></svg></button>
          <button class="ml-4"><svg class="w-6 h-6 text-gray-500 hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M15.707 15.707a1 1 0 01-1.414 0l-5-5a1 1 0 010-1.414l5-5a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 010 1.414zm-6 0a1 1 0 01-1.414 0l-5-5a1 1 0 010-1.414l5-5a1 1 0 011.414 1.414L5.414 10l4.293 4.293a1 1 0 010 1.414z" clip-rule="evenodd"></path></svg></button>
          <button class="ml-4"><svg class="w-6 h-6 text-gray-500 hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zM9.555 7.168A1 1 0 008 8v4a1 1 0 001.555.832l3-2a1 1 0 000-1.664l-3-2z" clip-rule="evenodd"></path></svg></button>
          <button class="ml-4"><svg class="w-6 h-6 text-gray-500 hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.293 15.707a1 1 0 010-1.414L14.586 10l-4.293-4.293a1 1 0 111.414-1.414l5 5a1 1 0 010 1.414l-5 5a1 1 0 01-1.414 0z" clip-rule="evenodd"></path><path fill-rule="evenodd" d="M4.293 15.707a1 1 0 010-1.414L8.586 10 4.293 5.707a1 1 0 011.414-1.414l5 5a1 1 0 010 1.414l-5 5a1 1 0 01-1.414 0z" clip-rule="evenodd"></path></svg></button>

          </div>
          <div class="flex items-center max-w-full justify-center mt-2">
            <div class="text-xs text-gray-500 mr-2">1:20</div>
            <div class="border border-gray-500 bg-gray-500 rounded-lg h-1 w-96 "></div>
            <div class="ml-2 text-xs text-gray-500">3:20</div>
          </div>
        </div>
        <div class="flex items-center justify-center px-6">
          <button>
            <svg class="w-4 h-4 text-gray-500 hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M9.383 3.076A1 1 0 0110 4v12a1 1 0 01-1.707.707L4.586 13H2a1 1 0 01-1-1V8a1 1 0 011-1h2.586l3.707-3.707a1 1 0 011.09-.217zM14.657 2.929a1 1 0 011.414 0A9.972 9.972 0 0119 10a9.972 9.972 0 01-2.929 7.071 1 1 0 01-1.414-1.414A7.971 7.971 0 0017 10c0-2.21-.894-4.208-2.343-5.657a1 1 0 010-1.414zm-2.829 2.828a1 1 0 011.415 0A5.983 5.983 0 0115 10a5.984 5.984 0 01-1.757 4.243 1 1 0 01-1.415-1.415A3.984 3.984 0 0013 10a3.983 3.983 0 00-1.172-2.828 1 1 0 010-1.415z" clip-rule="evenodd"></path></svg>
          </button>
          <div class="border border-gray-500 bg-gray-500 rounded-lg h-1 w-16 ml-4 ">
          </div> 
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
  .sidebar-spotify::-webkit-scrollbar
  {
    width: 6px;
    background-color: #121212;
  }
  .sidebar-spotify::-webkit-scrollbar-thumb {
    border-radius: 8px;
    background-color: #535353;
  }
  .content-spotify::-webkit-scrollbar
  {
    width: 6px;
    background-color: #181818;
  }
  .content-spotify::-webkit-scrollbar-thumb {
    border-radius: 8px;
    background-color: #535353;
  }

</style>