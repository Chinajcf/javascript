#### callee属性->用法

      function calleeDemo(){
         console.log(arguments.callee)
      }
      calleeDemo();
      //打印整个calleeDemo函数

#### caller属性->用法

      function callerDemo() {
        console.log(callerDemo.caller)
      }
      function handleCaller() {
        callerDemo();
      }
      handleCaller();
      //哪个函数调用callerDemo函数,则输出调用callerDemo函数的函数
