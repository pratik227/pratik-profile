<template>
  <q-layout view="lHh Lpr lFf" style="background-color: #0a182e !important;">
    <q-header reveal class="card-color2 q-pa-sm no-shadow" style="height: 60px">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar rounded text-color="white" class="rounded-borders" style="border: 1px solid white">P</q-avatar>
        </q-toolbar-title>

        <div class="text-color q-mx-md cursor-pointer text-weight-bolder" @click="$root.$emit('goAbout')">01. About</div>
        <div class="text-color q-mx-md cursor-pointer text-weight-bolder" @click="$root.$emit('goProjects')">02. Projects</div>
        <div class="text-color q-mx-md cursor-pointer text-weight-bolder" @click="$root.$emit('goSponsors')">0.3 Sponsors</div>
        <div class="text-color q-mx-md cursor-pointer text-weight-bolder" @click="$root.$emit('goContact')">0.4 Contact</div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view/>
    </q-page-container>
  </q-layout>
</template>

<script>
    import EssentialLink from 'components/EssentialLink'

    export default {
        name: 'MainLayout',

        components: {
            EssentialLink
        },

        data() {
            return {
                leftDrawerOpen: false,
                essentialLinks: [
                    {
                        title: 'Docs',
                        caption: 'quasar.dev',
                        icon: 'school',
                        link: 'https://quasar.dev'
                    },
                    {
                        title: 'Github',
                        caption: 'github.com/quasarframework',
                        icon: 'code',
                        link: 'https://github.com/quasarframework'
                    },
                    {
                        title: 'Discord Chat Channel',
                        caption: 'chat.quasar.dev',
                        icon: 'chat',
                        link: 'https://chat.quasar.dev'
                    },
                    {
                        title: 'Forum',
                        caption: 'forum.quasar.dev',
                        icon: 'record_voice_over',
                        link: 'https://forum.quasar.dev'
                    },
                    {
                        title: 'Twitter',
                        caption: '@quasarframework',
                        icon: 'rss_feed',
                        link: 'https://twitter.quasar.dev'
                    },
                    {
                        title: 'Facebook',
                        caption: '@QuasarFramework',
                        icon: 'public',
                        link: 'https://facebook.quasar.dev'
                    },
                    {
                        title: 'Quasar Awesome',
                        caption: 'Community Quasar projects',
                        icon: 'favorite',
                        link: 'https://awesome.quasar.dev'
                    }
                ]
            }
        }
    }
</script>
