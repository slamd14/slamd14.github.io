# Introduction to Web Applications

## Introduction

## Web Applications vs. Websites

## Web Applications vs. Native Operating System Applications

## Web Application Distribution

## Security Risks of Web Applications

最常见的过程之一是首先检查 Web 应用程序的前端组件，例如HTML和CSS（JavaScript也称为前端三位一体），并尝试查找敏感数据暴露和跨站点脚本 (XSS)等漏洞. 一旦所有前端组件都经过彻底测试，我们通常会检查 Web 应用程序的核心功能以及浏览器和 Web 服务器之间的交互，以列举 Web 服务器使用的技术并寻找可利用的缺陷。我们通常从未经身份验证和经过身份验证的角度（如果应用程序具有登录功能）评估 Web 应用程序，以最大限度地扩大覆盖范围并审查每个可能的攻击场景。

## Attacking Web Applications
如今，通过已知的公共漏洞（例如易受攻击的服务或 Windows 远程代码执行 (RCE) 漏洞）直接利用面向外部的主机并不常见，尽管它确实发生了。Web 应用程序提供了一个巨大的攻击面，它们的动态特性意味着它们不断变化（并且被忽视！）。一个相对简单的代码更改可能会引入一个灾难性漏洞或一系列漏洞，这些漏洞可以链接在一起以获取对 Web 服务器或环境中其他主机（例如数据库服务器）上的敏感数据或远程代码执行的访问权限。

