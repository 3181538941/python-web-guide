.. _goweb:

Go入门
=====================================================================

go语言
--------------------------------------------------

`The-way-to-go <https://github.com/Unknwon/the-way-to-go_ZH_CN>`_
`golang-developer-roadmap <https://github.com/Alikhll/golang-developer-roadmap>`_


GOPROXY 代理
--------------------------------------------------
export GOPROXY=https://goproxy.io


Web框架
--------------------------------------------------


单元测试
--------------------------------------------------

`GoMock框架使用指南 <https://www.jianshu.com/p/f4e773a1b11f>`_


Go 调试器dlv
---------------------------------------------------------------

.. code-block:: shell

   # go get -u github.com/derekparker/delve/cmd/dlv
   dlv debug main.go

   # 加上命令行参数
   # https://github.com/go-delve/delve/issues/562
   dlv debug ./cmd/unit-assignment-cli/main.go -- server

   # 搜索函数，打断点
   funcs FuncName
