<template>
    <my-page title="办公" :page="page">
        <app-list :data="groups" />
    </my-page>
</template>

<script>
    export default {
        data () {
            return {
                groups: [
                    {
                        name: '分类',
                        apps: [
                            {
                                name: '文本',
                                desc: '',
                                icon: '/static/img/text.svg',
                                to: 'xxx',
                                href: 'https://text.yunser.com/',
                                target: '_blank'
                            },
                            // {
                            //     name: '文档',
                            //     desc: '',
                            //     icon: '/static/img/doc.svg',
                            //     to: '/doc'
                            // },
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
                    },
                    {
                        name: '其他',
                        apps: [
                            {
                                name: 'Link',
                                desc: '快速定制属于自己的工具',
                                icon: '/static/img/link.svg',
                                to: 'xxx',
                                href: 'https://link.yunser.com/',
                                target: '_blank'
                            },
                            {
                                name: '文档',
                                desc: '',
                                icon: '/static/img/doc.svg',
                                to: 'xxx',
                                href: 'http://doc.yunser.com/',
                                target: '_blank'
                            },
                            {
                                name: '表格',
                                desc: '',
                                icon: '/static/img/table.svg',
                                to: 'xxx',
                                href: 'https://table.yunser.com',
                                target: '_blank'
                            },
                            {
                                name: '演示',
                                desc: '',
                                icon: '/static/img/display.svg',
                                to: 'xxx',
                                href: 'https://page.yunser.com',
                                target: '_blank'
                            },
                            {
                                name: '图形制作',
                                desc: '',
                                icon: '/static/img/shape.svg',
                                to: 'xxx',
                                href: 'https://svg.yunser.com/',
                                target: '_blank'
                            },
                            {
                                name: '云盘',
                                desc: '',
                                icon: '/static/img/doc.svg',
                                to: 'xxx',
                                href: 'http://file.yunser.com/',
                                target: '_blank'
                            },
                            {
                                name: '临时网盘',
                                desc: '',
                                icon: '/static/img/file_temp.svg',
                                to: 'xxx',
                                href: 'https://file.yunser.com/temp/',
                                target: '_blank'
                            },
                            {
                                name: '格式转换',
                                desc: '',
                                icon: '/static/img/convert.svg',
                                to: 'xxx',
                                href: 'https://converter.yunser.com/',
                                target: '_blank'
                            },
                            {
                                name: '原型图制作',
                                desc: '用图片制作原型图',
                                icon: '/static/img/convert.svg',
                                to: 'xxx',
                                href: 'https://builder.yunser.com/',
                                target: '_blank'
                            }
                        ]
                    },
                    {
                        name: '其他',
                        apps: [
                            {
                                name: '图片批量下载',
                                desc: '',
                                icon: '/static/img/link.svg',
                                to: 'xxx',
                                href: 'https://download.yunser.com/',
                                target: '_blank'
                            },
                            {
                                name: '字体生成',
                                desc: '',
                                icon: '/static/img/font.svg',
                                to: 'xxx',
                                href: 'https://font.yunser.com',
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
