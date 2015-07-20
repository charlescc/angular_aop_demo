1./js/
angular.js&&angular-aop.js源文件
2./private/
test_aop.html angularaop的demo

test_aop主要通过Angular的Service将Authorization和Logger封装成单独的Service,再通过AngularAOP的executeProvider的方式来在特定的目标函数达到某个执行阶段时执行。而不是直接将Authorization和Logger在目标函数体内进行调用，降低了代码耦合，方便代码维护。
详情查看原作者[GitHub](https://github.com/mgechev/angular-aop 'GitHub')