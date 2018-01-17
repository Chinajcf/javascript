### Math对象
        函数属性:
              abs():
                返回输入数字的绝对值,但具有正号
                  1.如果x的是NaN,则返回NaN
                  2.如果x是-0,结果是+0
                  3.如果x是-infinity,结果是+infinity
                用法:
                  Math.abs(x)

              acos():
                返回x的反余弦的依赖于实现的近似值 结果以弧度表示,范围从+0到+π
                  1.如果x大于或者小于1,结果是NaN
                  2.如果x等于1,结果是+0
                  3.如果x是NaN,那么结果是NaN
                用法:
                  Math.acos(x)

              asin():
                返回x的反正弦的依赖于实现的近似值 结果以弧度表示,范围从-π/2到+π/2
                  1.如果x是NaN,那么结果是NaN
                  2.如果x大于1,结果是NaN
                  3.如果x小于-1,结果是NaN
                  4.如果x是+0,结果是+0
                  5.如果x是-0,结果是-0

              floor():
                向下取整,例如x是1.999 则输出1
                  1.如果x是NaN,则输出NaN
                  2.如果x是-0,则输出-0
                  3.如果x是+0,则输出+0
                  4.如果x是+infinity,则输出+infinity
                  5.如果x是-infinity,则输出+0
                用法:
                  Math.floor(x)
                  
              ceil():向上取整，例如x是1.1 则输出2
                        
              max():
                返回最大的那个数字
                  1.如果没给参数返回-Infinity
                  2.如果有任何值是NaN则返回NaN
                用法：
                  Math.max(x,y)//取最大的值

              min():
                返回最小的那个数字
                  1.如果没给参数返回+Infinity
                  2.如果有任何值是NaN则返回NaN
                用法：
                  Math.max(x,y)//取最小的值

              pow():
                里面两个参数 x的y次幂

                用法：
                  Math.pow(x,y)

              random():
                返回0-1(不包括1)之间的随机数
                用法:
                  Math.random()

              round():
                以四舍五入的方式取x值
                用法:
                  Math.round()

              sqrt():
                返回x的平方根 例如:  4->2   16->4
                用法:
                  Math.sqrt()

              
