    <template>
    <div>
        <div class="h-screen flex flex-col">
            <header class="flex flex-shrink-0">
                <div class="w-64 bg-gray-800 px-4 py-3 flex-shrink-0">
                    <button class="block w-full flex items-center">
                        <img class="h-8 w-8 rounded-full object-cover"
                        src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=144&q=80" alt="">
                        <span class="text-white font-medium text-sm ml-4 mr-2">Susan Wanjira</span>
                        <svg class="ml-auto h-6 w-6 stroke-current text-gray-400" fill="none" viewBox="0 0 24 24">
                        <path d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"/>
                        </svg>
                    </button>
                </div>
                <div class="bg-gray-700 flex-1 flex justify-between items-center">
                    <nav class="flex ml-6">
                        <a href="#" class="ml-2 inline-block px-3 py-2 leading-none bg-gray-800 text-sm rounded-lg font-medium text-white">Mailbox</a>
                        <a href="#" class="ml-2 inline-block px-3 py-2 leading-none text-sm rounded-lg hover:bg-gray-600 font-medium text-white">Customer</a>
                        <a href="#" class="ml-2 inline-block px-3 py-2 leading-none text-sm rounded-lg hover:bg-gray-600 font-medium text-white">Reporting</a>
                        <a href="#" class="ml-2 inline-block px-3 py-2 leading-none text-sm rounded-lg hover:bg-gray-600 font-medium text-white">Manage</a>
                    </nav>
                    <div class="flex items-center mr-6">
                        <div class="relative w-64">
                            <span class="absolute inset-y-0 left-0 flex items-center pl-2">
                                <svg class="fill-current h-5 w-5 text-gray-500" viewBox="0 0 24 24">
                                    <path d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z"/>
                                </svg>
                            </span>
                            <input class="block w-full pl-8 pr-4 py-2 bg-gray-900 rounded-lg text-sm placeholder-gray-400 docus:outline-none focus:bg-white focus:text-gray-900 focus:placeholder-gray-700" placeholder="Search..">
                        </div>
                        <button class="ml-5 text-gray-400 hover:text-gray-200">
                            <svg class="fill-current h-5 w-5" viewBox="0 0 24 24">
                            <path d="M15 19a3 3 0 0 1-6 0H4a1 1 0 0 1 0-2h1v-6a7 7 0 0 1 4.02-6.34 3 3 0 0 1 5.96 0A7 7 0 0 1 19 11v6h1a1 1 0 0 1 0 2h-5zm-4 0a1 1 0 0 0 2 0h-2zm0-12.9A5 5 0 0 0 7 11v6h10v-6a5 5 0 0 0-4-4.9V5a1 1 0 0 0-2 0v1.1z"/>
                            </svg>
                        </button>
                        <button class="ml-5 text-gray-400 hover:text-gray-200">
                        <svg class="fill-current h-5 w-5" viewBox="0 0 24 24">
                            <path d="M12 2a10 10 0 1 1 0 20 10 10 0 0 1 0-20zm0 2a8 8 0 1 0 0 16 8 8 0 0 0 0-16zm0 9a1 1 0 0 1-1-1V8a1 1 0 0 1 2 0v4a1 1 0 0 1-1 1zm0 4a1 1 0 1 1 0-2 1 1 0 0 1 0 2z"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </header>
            <div class="flex-1 flex overflow-hidden">
                <aside class="w-64 p-6 bg-gray-100 flex-shrink-0 overflow-y-auto">
                    <nav>
                        <h2 class="text-xs font-semibold text-gray-600 tracking-wide uppercase">Mailboxes</h2>
                        <div class="mt-3">
                            <a href="" class="mt-4 text-sm font-medium flex items-center justify-between bg-gray-200 rounded-lg -mx-3 px-2 py-1 ">
                                <span class="inline-flex">
                                    <svg class="fill-current h-6 w-6 text-gray-700" viewBox="0 0 24 24">
                                        <path d="M18 2a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4c0-1.1.9-2 2-2h16zm-4.37 9.1L20 16v-2l-5.12-3.9L20 6V4l-10 8L0 4v2l5.12 4.1L0 14v2l6.37-4.9L10 14l3.63-2.9z"/>
                                    </svg>
                                    <span class="ml-3 text-gray-900">Inbox</span>
                                </span>
                                <span class="font-semibold text-xs text-gray-700 bg-gray-300 rounded-full w-8 py-1 leading-none inline-block text-center">6</span>
                            </a>
                            <a href="" class="mt-4 text-sm font-medium flex items-center justify-between hover:bg-gray-200 hover:rounded-lg -mx-3 px-2 py-1 ">
                                <span class="inline-flex">
                                        <svg class="fill-current h-6 w-6 text-gray-500" viewBox="0 0 20 20">
                                           <path d="M4 16v5a1 1 0 0 1-2 0V3a1 1 0 0 1 1-1h8.5a1 1 0 0 1 .7.3l.71.7H21a1 1 0 0 1 .9 1.45L19.11 10l2.77 5.55A1 1 0 0 1 21 17h-8.5a1 1 0 0 1-.7-.3l-.71-.7H4zm7-12H4v10h7.5a1 1 0 0 1 .7.3l.71.7h6.47l-2.27-4.55a1 1 0 0 1 0-.9L19.38 5H13v4a1 1 0 0 1-2 0V4z"/>
                                        </svg>
                                    <span class="ml-3 text-gray-700">Flagged</span>
                                </span>
                            </a>
                            <a href="" class="mt-4 text-sm font-medium flex items-center justify-between hover:bg-gray-200 hover:rounded-lg -mx-3 px-2 py-1 ">
                                <span class="inline-flex">
                                    <svg class="fill-current h-6 w-6 text-gray-500" viewBox="0 0 24 24">
                                        <path d="M6.3 12.3l10-10a1 1 0 0 1 1.4 0l4 4a1 1 0 0 1 0 1.4l-10 10a1 1 0 0 1-.7.3H7a1 1 0 0 1-1-1v-4a1 1 0 0 1 .3-.7zM8 16h2.59l9-9L17 4.41l-9 9V16zm10-2a1 1 0 0 1 2 0v6a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6c0-1.1.9-2 2-2h6a1 1 0 0 1 0 2H4v14h14v-6z"/>
                                    </svg>
                                    <span class="ml-3 text-gray-700">Drafts</span>
                                </span>
                                <span class="font-semibold text-xs text-gray-700 bg-gray-300 rounded-full w-8 py-1 leading-none inline-block text-center">2</span>
                            </a>
                            <a href="" class="mt-4 text-sm font-medium flex items-center justify-between hover:bg-gray-200 hover:rounded-lg -mx-3 px-2 py-1 ">
                                <span class="inline-flex">
                                    <svg class="fill-current h-6 w-6 text-gray-500" viewBox="0 0 24 24">
                                        <path d="M5 5a5 5 0 0 1 10 0v2A5 5 0 0 1 5 7V5zM0 16.68A19.9 19.9 0 0 1 10 14c3.64 0 7.06.97 10 2.68V20H0v-3.32z"/>
                                    </svg>
                                    <span class="ml-3 text-gray-700">Assigned</span>
                                </span>
                                <span class="font-semibold text-xs text-gray-700 bg-gray-300 rounded-full w-8 py-1 leading-none inline-block text-center">1</span>
                            </a>
                            <a href="" class="mt-4 text-sm font-medium flex items-center justify-between hover:bg-gray-200 hover:rounded-lg -mx-3 px-2 py-1 ">
                                <span class="inline-flex">
                                    <svg class="fill-current h-6 w-6 text-gray-500" viewBox="0 0 24 24">
                                        <path d="M2.93 17.07A10 10 0 1 1 17.07 2.93 10 10 0 0 1 2.93 17.07zm12.73-1.41A8 8 0 1 0 4.34 4.34a8 8 0 0 0 11.32 11.32zM6.7 9.29L9 11.6l4.3-4.3 1.4 1.42L9 14.4l-3.7-3.7 1.4-1.42z"/>
                                    </svg>
                                    <span class="ml-3 text-gray-700">Closed</span>
                                </span>
                            </a>
                            <a href="" class="mt-4 text-sm font-medium flex items-center justify-between hover:bg-gray-200 hover:rounded-lg -mx-3 px-2 py-1 ">
                                <span class="inline-flex">
                                    <svg class="fill-current h-6 w-6 text-gray-500" viewBox="0 0 24 24">
                                        <path d="M20 9v10a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V9a2 2 0 0 1-2-2V5c0-1.1.9-2 2-2h16a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2zm0-2V5H4v2h16zM6 9v10h12V9H6zm4 2h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2z"/>
                                    </svg>
                                    <span class="ml-3 text-gray-700">Junk</span>
                                </span>
                                <span class="font-semibold text-xs text-gray-700 bg-gray-300 rounded-full w-8 py-1 leading-none inline-block text-center">6</span>
                            </a>
                        </div>
                         <h2 class="mt-8 text-xs font-semibold text-gray-600 tracking-wide uppercase">Folders</h2>
                        <div class="mt-3">
                            <a href="" class="block text-sm font-medium text-gray-700">Refunds</a>
                            <a href="" class="block text-sm font-medium mt-4 text-gray-700">Discounts</a>
                            <a href="" class="block text-sm font-medium mt-4 text-gray-700">Bugs</a>
                        </div>
                    </nav>
                </aside>
                <main class="flex-1 flex flex-shrink-0 bg-gray-200 overflow-hidden">
                    <div class="relative flex flex-col w-full max-w-xs flex-grow border-l border-r border-b bg-gray-200">
                        <div class="flex flex-shrink-0 px-4 py-2 items-center justify-between">
                            <button class="flex items-center text-xs font-semibold text-gray-600">
                                Sorted by date
                                <svg class="ml-2 h-6 w-6 stroke-current text-gray-500" fill="none" viewBox="0 0 24 24">
                                    <path d="M16 10l-4 4-4-4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                </svg>
                            </button>
                            <button>
                                <svg class="h-6 w-6 fill-current text-gray-500" viewBox="0 0 24 24">
                                    <path d="M20 15a1 1 0 0 0 2 0V7a1 1 0 0 0-1-1h-8a1 1 0 0 0 0 2h5.59L13 13.59l-3.3-3.3a1 1 0 0 0-1.4 0l-6 6a1 1 0 0 0 1.4 1.42L9 12.4l3.3 3.3a1 1 0 0 0 1.4 0L20 9.4V15z"/>
                                </svg>
                            </button>
                        </div>
                        <div class="overflow-y-auto">
                            <a href="#" class="block px-6 pt-3 pb-4 bg-white">
                                <div class="flex justify-between">
                                    <span class="text-sm font-semibold text-gray-900">Margaret Githinji</span>
                                    <span class="text-sm text-gray-600">2 days</span>
                                </div>
                                <p class="text-sm text-gray-900">Refund</p>
                                <p class="text-sm text-gray-600 mt-2 ">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis consecte akba....</p>
                            </a> 
                            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
                                <div class="flex justify-between">
                                    <span class="text-sm font-semibold text-gray-900">Margaret Githinji</span>
                                    <span class="text-sm text-gray-600">2 days</span>
                                </div>
                                <p class="text-sm text-gray-900">Refund</p>
                                <p class="text-sm text-gray-600 mt-2 ">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis consecte akba....</p>
                            </a> 
                            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
                                <div class="flex justify-between">
                                    <span class="text-sm font-semibold text-gray-900">Margaret Githinji</span>
                                    <span class="text-sm text-gray-600">2 days</span>
                                </div>
                                <p class="text-sm text-gray-900">Refund</p>
                                <p class="text-sm text-gray-600 mt-2 ">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis consecte akba....</p>
                            </a> 
                            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
                                <div class="flex justify-between">
                                    <span class="text-sm font-semibold text-gray-900">Margaret Githinji</span>
                                    <span class="text-sm text-gray-600">2 days</span>
                                </div>
                                <p class="text-sm text-gray-900">Refund</p>
                                <p class="text-sm text-gray-600 mt-2 ">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis consecte akba....</p>
                            </a> 
                            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
                                <div class="flex justify-between">
                                    <span class="text-sm font-semibold text-gray-900">Margaret Githinji</span>
                                    <span class="text-sm text-gray-600">2 days</span>
                                </div>
                                <p class="text-sm text-gray-900">Refund</p>
                                <p class="text-sm text-gray-600 mt-2 ">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis consecte akba....</p>
                            </a> 
                            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
                                <div class="flex justify-between">
                                    <span class="text-sm font-semibold text-gray-900">Margaret Githinji</span>
                                    <span class="text-sm text-gray-600">2 days</span>
                                </div>
                                <p class="text-sm text-gray-900">Refund</p>
                                <p class="text-sm text-gray-600 mt-2 ">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis consecte akba....</p>
                            </a> 
                            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
                                <div class="flex justify-between">
                                    <span class="text-sm font-semibold text-gray-900">Margaret Githinji</span>
                                    <span class="text-sm text-gray-600">2 days</span>
                                </div>
                                <p class="text-sm text-gray-900">Refund</p>
                                <p class="text-sm text-gray-600 mt-2 ">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis consecte akba....</p>
                            </a> 
                            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
                                <div class="flex justify-between">
                                    <span class="text-sm font-semibold text-gray-900">Margaret Githinji</span>
                                    <span class="text-sm text-gray-600">2 days</span>
                                </div>
                                <p class="text-sm text-gray-900">Refund</p>
                                <p class="text-sm text-gray-600 mt-2 ">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis consecte akba....</p>
                            </a> 
                            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
                                <div class="flex justify-between">
                                    <span class="text-sm font-semibold text-gray-900">Margaret Githinji</span>
                                    <span class="text-sm text-gray-600">2 days</span>
                                </div>
                                <p class="text-sm text-gray-900">Refund</p>
                                <p class="text-sm text-gray-600 mt-2 ">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis consecte akba....</p>
                            </a> 
                            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
                                <div class="flex justify-between">
                                    <span class="text-sm font-semibold text-gray-900">Margaret Githinji</span>
                                    <span class="text-sm text-gray-600">2 days</span>
                                </div>
                                <p class="text-sm text-gray-900">Refund</p>
                                <p class="text-sm text-gray-600 mt-2 ">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis consecte akba tahllatlajaljtlajtla....</p>
                            </a> 
                            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-t">
                                <div class="flex justify-between">
                                    <span class="text-sm font-semibold text-gray-900">Margaret Githinji</span>
                                    <span class="text-sm text-gray-600">2 days</span>
                                </div>
                                <p class="text-sm text-gray-900">Refund</p>
                                <p class="text-sm text-gray-600 mt-2 ">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis consecte akba....</p>
                            </a> 
                        </div>
                    </div>
                    <div class="flex-1 flex flex-col min-w-0">
                        <div class="relative shadow-md">
                            <div class="flex items-center justify-between py-4 px-5 bg-gray-100 border-b">
                                <div class="flex items-center">
                                    <button>
                                        <svg viewBox="0 0 24 24" class="fill-current w-6 h-6 text-gray-600">
                                            <path d="M5.41 11H21a1 1 0 0 1 0 2H5.41l5.3 5.3a1 1 0 0 1-1.42 1.4l-7-7a1 1 0 0 1 0-1.4l7-7a1 1 0 0 1 1.42 1.4L5.4 11z"/>
                                        </svg>
                                    </button>
                                    <button class="ml-4">
                                        <svg viewBox="0 0 24 24" class="fill-current w-6 h-6 text-gray-600">
                                            <path d="M2.59 13.41A1.98 1.98 0 0 1 2 12V7a5 5 0 0 1 5-5h4.99c.53 0 1.04.2 1.42.59l8 8a2 2 0 0 1 0 2.82l-8 8a2 2 0 0 1-2.82 0l-8-8zM20 12l-8-8H7a3 3 0 0 0-3 3v5l8 8 8-8zM7 8a1 1 0 1 1 0-2 1 1 0 0 1 0 2z"/>
                                        </svg>
                                    </button>
                                    <button class="ml-4">
                                        <svg class="fill-current h-6 w-6 text-gray-600" viewBox="0 0 24 24">
                                            <path d="M5 5a5 5 0 0 1 10 0v2A5 5 0 0 1 5 7V5zM0 16.68A19.9 19.9 0 0 1 10 14c3.64 0 7.06.97 10 2.68V20H0v-3.32z"/>
                                        </svg>
                                    </button>
                                    <button class="ml-4">
                                        <svg viewBox="0 0 24 24" class="fill-current w-6 h-6 text-gray-600">
                                            <path d="M20 6a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6c0-1.1.9-2 2-2h7.41l2 2H20zM4 6v12h16V8h-7.41l-2-2H4zm12 7a1 1 0 0 1-1 1H9a1 1 0 0 1 0-2h6a1 1 0 0 1 1 1z"/>
                                        </svg>
                                    </button>
                                    <button class="ml-4">
                                        <svg viewBox="0 0 24 24" class="fill-current w-6 h-6 text-gray-600">
                                            <path  d="M4 15a3 3 0 1 1 0-6 3 3 0 0 1 0 6zm0-2a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm8 2a3 3 0 1 1 0-6 3 3 0 0 1 0 6zm0-2a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm8 2a3 3 0 1 1 0-6 3 3 0 0 1 0 6zm0-2a1 1 0 1 0 0-2 1 1 0 0 0 0 2z"/>
                                        </svg>
                                    </button>
                                </div>
                                <div class="flex items-center">
                                    <button>
                                        <svg viewBox="0 0 24 24" class="fill-current w-6 h-6 text-gray-600">
                                        <path class="heroicon-ui" d="M8.7 14.7a1 1 0 0 1-1.4-1.4l4-4a1 1 0 0 1 1.4 0l4 4a1 1 0 0 1-1.4 1.4L12 11.42l-3.3 3.3z"/>
                                        </svg>
                                    </button>
                                    <button class="ml-2">
                                        <svg viewBox="0 0 24 24" class="fill-current w-6 h-6 text-gray-600">
                                            <path class="heroicon-ui" d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"/>
                                        </svg>
                                    </button>
                                </div>
                            </div>
                            <div class="bg-white px-5 flex justify-between items-center py-4 shadow-md">
                                <h3 class="text-xl text-gray-900 truncate">RE: Student Discount Lorem, ipsum d maximei dolorem ipsum d maximei dolorem  ?</h3>
                                <div class="ml-4 flex-shrink-0">
                                    <span>#1428</span>
                                    <span class="ml-2 text-sm font-semibold text-green-900 rounded-full bg-green-200 leading-none px-2 py-1">Active</span>
                                </div>
                            </div>
                        </div>
                        <div class="p-3 flex-1 overflow-y-auto">
                            <article class="bg-white rounded-lg px-10 py-6 mb-2 shadow">
                                <div class="flex items-center justify-between">
                                    <p class="text-lg font-semibold">
                                        <span class="text-gray-900">Samantha Nyawira</span>
                                        <span class="text-gray-600 ml-2">wrote</span>
                                    </p>
                                    <div class="flex items-center">
                                        <span class="text-sm text-gray-600">Yesterday at 7.14 am</span>
                                        <img class="ml-5 h-8 w-8 rounded-full object-cover" src="https://images.unsplash.com/photo-1463453091185-61582044d556?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=144&q=80" alt="">
                                    </div>
                                </div>
                                <div>
                                    <p class="mt-6 text-gray-800 text-sm">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Deserunt nesciunt veniam quas ipsam illum dolore dicta, sunt facilis ipsa autem ut, sint amet? Eius, doloremque vel nesciunt deserunt harum fuga.</p>
                                </div>
                            </article>
                            <article class="bg-white rounded-lg px-10 py-6 mb-2 shadow">
                                <div class="flex items-center justify-between">
                                    <p class="text-lg font-semibold">
                                        <span class="text-gray-900">Susan Wanjira</span>
                                        <span class="text-gray-600 ml-2">wrote</span>
                                    </p>
                                    <div class="flex items-center">
                                        <span class="text-sm text-gray-600">Yesterday at 7.14 am</span>
                                        <img class="ml-5 h-8 w-8 rounded-full object-cover" src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=144&q=80" alt="">
                                    </div>
                                </div>
                                <div>
                                    <p class="mt-6 text-gray-800 text-sm">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Deserunt nesciunt veniam quas ipsam illum dolore dicta, sunt facilis ipsa autem ut, sint amet? Eius, doloremque vel nesciunt deserunt harum fuga.</p>
                                    <p class="mt-6 text-gray-800 text-sm">
                                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque sunt perspiciatis error minima deleniti esse repudiandae sequi, totam mollitia provident molestias iure impedit animi consectetur repellendus vel, quaerat rerum! Debitis.
                                    </p>
                                    <p class="mt-6 text-sm font-semibold">
                                        Monica White
                                    </p>
                                    <p class="text-sm text-gray-800">
                                        Customer Service
                                    </p>
                                </div>
                            </article>
                            <article class="bg-white rounded-lg px-10 py-6 mb-2 shadow">
                                <div class="flex items-center justify-between">
                                    <p class="text-lg font-semibold">
                                        <span class="text-gray-900">Samantha Nyawira</span>
                                        <span class="text-gray-600 ml-2">wrote</span>
                                    </p>
                                    <div class="flex items-center">
                                        <span class="text-sm text-gray-600">Yesterday at 7.14 am</span>
                                        <img class="ml-5 h-8 w-8 rounded-full object-cover" src="https://images.unsplash.com/photo-1463453091185-61582044d556?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=144&q=80" alt="">
                                    </div>
                                </div>
                                <div>
                                    <p class="mt-6 text-gray-800 text-sm">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Deserunt nesciunt veniam quas ipsam illum dolore dicta, sunt facilis ipsa autem ut, sint amet? Eius, doloremque vel nesciunt deserunt harum fuga.</p>
                                </div>
                            </article>
                            <article class="bg-white rounded-lg px-10 py-6 mb-2 shadow">
                                <div class="flex items-center justify-between">
                                    <p class="text-lg font-semibold">
                                        <span class="text-gray-900">Samantha Nyawira</span>
                                        <span class="text-gray-600 ml-2">wrote</span>
                                    </p>
                                    <div class="flex items-center">
                                        <span class="text-sm text-gray-600">Yesterday at 7.14 am</span>
                                        <img class="ml-5 h-8 w-8 rounded-full object-cover" src="https://images.unsplash.com/photo-1463453091185-61582044d556?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=144&q=80" alt="">
                                    </div>
                                </div>
                                <div>
                                    <p class="mt-6 text-gray-800 text-sm">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Deserunt nesciunt veniam quas ipsam illum dolore dicta, sunt facilis ipsa autem ut, sint amet? Eius, doloremque vel nesciunt deserunt harum fuga.</p>
                                </div>
                            </article>
                        </div>
                    </div>
                </main>
            </div>
        </div>
    </div>   
</template>

<script>
export default {

}
</script>

<style src="../assets/tailwind.css">

</style>
