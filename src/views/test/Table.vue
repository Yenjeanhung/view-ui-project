<template>
    <Table :columns="list_title" :data="customerList"></Table>

</template>
<script>
    export default {
        data () {
            return {
                list_title: [
                    {
                        title: '姓名',
                        key: 'name'
                    },
                    {
                        title: '年龄',
                        key: 'age'
                    },
                    {
                        title: '地址',
                        key: 'address'
                    },
                    {
                        title: '创建时间',
                        key: 'date'
                    }
                ],
                customerList: [

                    {
                        name: '张三',
                        age: 29,
                        address: '北京 昌平',
                        date: '2020-02-01'
                    },
                    {
                        name: '李四',
                        age: 28,
                        address: '北京 朝阳',
                        date: '2020-01-31'
                    },
                    {
                        name: 'John Brown',
                        age: 18,
                        address: 'New York No. 1 Lake Park',
                        date: '2016-10-03'
                    },
                    {
                        name: 'Jim Green',
                        age: 24,
                        address: 'London No. 1 Lake Park',
                        date: '2016-10-01'
                    },
                    {
                        name: 'Joe Black',
                        age: 30,
                        address: 'Sydney No. 1 Lake Park',
                        date: '2016-10-02'
                    },
                    {
                        name: 'Jon Snow',
                        age: 26,
                        address: 'Ottawa No. 2 Lake Park',
                        date: '2016-10-04'
                    }
                ]
            }
        }
    }
</script>
