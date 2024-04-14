<div class="hidden space-x-8 sm:-my-px sm:ml-10 sm:flex">
    <NavLink :href="route('dashboard')" :active="route().current('dashboard')">
        Dashboard
    </NavLink>
    <NavLink :href="route('chirps.index')" :active="route().current('chirps.index')">
        Chirps
    </NavLink>
</div>
<div class="pt-2 pb-3 space-y-1">
    <ResponsiveNavLink :href="route('dashboard')" :active="route().current('dashboard')">
        Dashboard
    </ResponsiveNavLink>
    <ResponsiveNavLink :href="route('chirps.index')" :active="route().current('chirps.index')">
        Chirps
    </ResponsiveNavLink>
</div>
