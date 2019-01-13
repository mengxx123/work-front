<template>
    <my-page title="角色" :page="page">
        <app-list :data="groups" />
    </my-page>
</template>

<script>
    export default {
        data () {
            return {
                groups: [
                    {
                        name: '运营',
                        apps: [
                            {
                                name: '短网址',
                                desc: '',
                                icon: 'https://network.yunser.com/static/img/url.svg',
                                to: 'xxx',
                                href: 'https://network.yunser.com/short_url',
                                target: '_blank'
                            },
                            {
                                name: '图片',
                                desc: '',
                                icon: '/static/img/image.svg',
                                to: 'xxx',
                                href: 'https://imagetool.yunser.com/',
                                target: '_blank'
                            },
                            {
                                name: '图表',
                                desc: '',
                                icon: '/static/img/chart.svg',
                                to: 'xxx',
                                href: 'https://chart.yunser.com/',
                                target: '_blank'
                            },
                            {
                                name: '音频',
                                desc: '',
                                icon: '/static/img/audio.svg',
                                to: 'xxx',
                                href: 'https://audio.yunser.com/',
                                target: '_blank'
                            },
                            {
                                name: '视频',
                                desc: '',
                                icon: '/static/img/video.svg',
                                to: 'xxx',
                                href: 'https://video.yunser.com/',
                                target: '_blank'
                            }
                        ]
                    }
                ],
                page: {
                    menu: [
                        {
                            type: 'icon',
                            icon: 'apps',
                            href: 'https://app.yunser.com/',
                            target: '_blank',
                            title: '应用'
                        }
                    ]
                }
            }
        }
    }
</script>

<style scoped>
</style>
