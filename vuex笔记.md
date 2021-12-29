

#### status

##### 获取值

> 

```js
第一种			this.$store.变量
第二种			mapState 辅助函数  =>  多用于computed 计算属性

```

##### 修改值

> 只能通过 mutations 

```js
const store = new Vuex.Store({
  state: {		count: 1	},
  mutations: {
    increment (state) { state.count++}
  }
})
```



### getters 计算属性

#### 访问

```js
属性访问	store.getters.属性
方法访问	store.getters.方法(value)

方法定义
getters: {
    func1: (state, v1){
        return state.one.filter(todo => todo.done)
    }
}
```

#### mapGetters



### mutations



