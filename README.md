# exercism-problem


C:\Users\kacpe>exercism download --exercise=hello-world --track=python

Downloaded to
C:\Users\kacpe\Exercism\python\hello-world

C:\Users\kacpe>pytest hello_world_test.py
============================= test session starts =============================
platform win32 -- Python 3.7.0, pytest-3.7.1, py-1.5.4, pluggy-0.7.1
rootdir: C:\Users\kacpe, inifile:

======================== no tests ran in 0.01 seconds =========================
ERROR: file not found: hello_world_test.py


C:\Users\kacpe>






C:\Users\kacpe>pytest Exercism\python\hello-world\hello_world_test.py
============================= test session starts =============================
platform win32 -- Python 3.7.0, pytest-3.7.1, py-1.5.4, pluggy-0.7.1
rootdir: C:\Users\kacpe, inifile:
collected 1 item

Exercism\python\hello-world\hello_world_test.py F                        [100%]

================================== FAILURES ===================================
__________________________ HelloWorldTest.test_hello __________________________

self = <hello_world_test.HelloWorldTest testMethod=test_hello>

    def test_hello(self):
>       self.assertEqual(hello_world.hello(), 'Hello, World!')
E       AssertionError: None != 'Hello, World!'

Exercism\python\hello-world\hello_world_test.py:10: AssertionError
========================== 1 failed in 0.16 seconds ===========================
