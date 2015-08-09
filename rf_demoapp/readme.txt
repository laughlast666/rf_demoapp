一、robotframework-selenium2library-master webdemoapp
中的一个模拟webapp测试案例，无需额外web服务器
二、关于运行：
1.主要env：Robot Framework 2.8.5 (Python 2.7.7 on win32)
2.运行所有案例：
2.1	eclipse运行要run cofig设置参数（如G:\workspace\rf_demoapp\login_tests）
2.2 cmd运行：到rundemo.py所在目录下rundemo.py login_tests【自动启动模拟服务器】
2.3 成功运行控制台信息参考：myeclipse
==============================================================================
Login Tests                                                                   
==============================================================================
Login Tests.Invalid Login :: A test suite containing tests related to inval...
==============================================================================
Invalid Username                                                      | PASS |
------------------------------------------------------------------------------
Invalid Password                                                      | PASS |
------------------------------------------------------------------------------
Invalid Username And Password                                         | PASS |
------------------------------------------------------------------------------
Empty Username                                                        | PASS |
------------------------------------------------------------------------------
Empty Password                                                        | PASS |
------------------------------------------------------------------------------
Empty Username And Password                                           | PASS |
------------------------------------------------------------------------------
Login Tests.Invalid Login :: A test suite containing tests related... | PASS |
6 critical tests, 6 passed, 0 failed
6 tests total, 6 passed, 0 failed
==============================================================================
Login Tests.Valid Login :: A test suite with a single test for valid login....
==============================================================================
Valid Login                                                           | PASS |
------------------------------------------------------------------------------
Login Tests.Valid Login :: A test suite with a single test for val... | PASS |
1 critical test, 1 passed, 0 failed
1 test total, 1 passed, 0 failed
==============================================================================
Login Tests                                                           | PASS |
7 critical tests, 7 passed, 0 failed
7 tests total, 7 passed, 0 failed
==============================================================================
Output:  G:\workspace\rf_demoapp\output.xml
Log:     G:\workspace\rf_demoapp\log.html
Report:  G:\workspace\rf_demoapp\report.html