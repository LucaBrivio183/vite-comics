<script>

export default {

    data() {
        return {
            LinksGroups: [{
                groupName: 'DC COMICS',
                list: [
                    {
                        name: 'Characters',
                        link: '#',
                        target: '_self',
                    }, {
                        name: 'Comics',
                        link: '#',
                        target: '_self',
                    }, {
                        name: 'Movies',
                        link: '#',
                        target: '_self',
                    }, {
                        name: 'TV',
                        link: '#',
                        target: '_self',
                    }, {
                        name: 'Games',
                        link: '#',
                        target: '_self',
                    }, {
                        name: 'Videos',
                        link: '#',
                        target: '_self',
                    }, {
                        name: 'news',
                        link: '#',
                        target: '_self',
                    }

                ]
            }, {
                groupName: 'SHOP',
                list: [
                    {
                        name: 'Shop DC',
                        link: '#',
                        target: '_self',
                    }, {
                        name: 'Shop DC Collectibles',
                        link: '#',
                        target: '_self',
                    },
                ]
            }
            ]
        }
    }
</script>

<template></template>

<style lang="scss" scoped>
@use 'src/styles/Variables.scss' as *;
@use 'src/styles/Common.scss' as *;
</style>