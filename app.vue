<template>
    <div class="container">
      <TitleBlock />
      <client-only placeholder="loading...">
        <Drawer />
        
      </client-only>
      <NuxtPage />
      <Footer />
    </div>
</template>
