<template>
    <div class="mb-2">
        <b-navbar togglelable="lg" type="dark" variant="dark">
            <b-navbar-brand :href="$router.options.base">ブログ</b-navbar-brand>
            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
            <b-navbar-nav>
                <b-nav-item :href="$router.options.base + 'profile'">プロフィール</b-nav-item> 
            </b-navbar-nav>  
        </b-navbar>
    </div>
</template>