title: "use"
tag: 'aa'
---

this.$set(v, 'aaa', '')

Object.assign(this.$data.form, this.$options.data().form)
Object.assign(this.$data, this.$options.data()) // 重置data对象到初始化状态

finally()
.catch(error => {  this.$message.error(error.msg)})

{ min: 3, max: 32, message: '长度在 3 到 32 个字符', trigger: 'blur' }
{ validator(r, v, b) { (/(^[1-9]\d*$)/).test(v) ? b() : b(new Error(' ')) } }