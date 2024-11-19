.<template>
    <div class="navbar bg-[#0B0C0C] text-[#E9EAEC] shadow-2xl">
        <div class="navbar-start">
            <div class="dropdown">
                <div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                        stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M4 6h16M4 12h8m-8 6h16" />
                    </svg>
                </div>
                <ul tabindex="0"
                    class="menu menu-sm dropdown-content bg-base-100 rounded-box z-[1] mt-3 w-52 p-2 shadow text-[#0B0C0C]">
                    <li><a>Home</a></li>
                    <li><a>Products</a></li>
                    <li><a>Contact</a></li>
                </ul>
            </div>
            <a
                class="btn btn-ghost text-xl transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-[1.02] duration-300">
                <img class="h-12 w-12" src="../assets/TSG.png" alt="">
            </a>
        </div>
        <div class="navbar-center hidden lg:flex">
            <ul class="menu menu-horizontal px-1">
                <li
                    class="transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-[1.02] duration-300 hover:bg-[#2A2E34] rounded-xl">
                    <a>Home</a></li>
                <li
                    class="transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-[1.02] duration-300 hover:bg-[#2A2E34] rounded-xl">
                    <a>Products</a></li>
                <li
                    class="transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-[1.02] duration-300 hover:bg-[#2A2E34] rounded-xl">
                    <a>Contact</a></li>
            </ul>
        </div>
        <div class="navbar-end text-[#2A2E34]">
            <a
                class="btn mr-2 bg-gradient-to-r from-[#FBE134] to-[#E4B61A] border-[#E4B61A] font-bold shadow-lg hover:from-[#fbe134] hover:to-[#e4a41a] hover:border-[#e4a41a] transition ease-in-out delay-150  hover:-translate-y-1 hover:scale-[1.02] duration-300">เข้าสู่ระบบ</a>
            <a
                class="btn mr-2 bg-gradient-to-r from-[#FBE134] to-[#E4B61A] border-[#E4B61A] font-bold shadow-lg hover:from-[#fbe134] hover:to-[#e4a41a] hover:border-[#e4a41a] transition ease-in-out delay-150  hover:-translate-y-1 hover:scale-[1.02] duration-300">สมัครเป็นพาร์ทเนอร์</a>
        </div>
    </div>
</template>

<script>

</script>
