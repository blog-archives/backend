---
title: Backend Development
order: 1
---

> roadmap lesson: https://roadmap.sh/packs/internet

后端开发专注于 Web 应用程序的服务器端逻辑，涉及数据的存储、处理以及安全性保障。这项工作包括构建和维护支持前端界面的基础设施，确保客户端与数据库之间的顺畅通信。具体任务包括创建 API、管理数据库，以及实施认证和授权机制等。

- [x] [video] [How The Backend Works](https://www.youtube.com/watch?v=4r6WdaY3SOA) (Youtube, Web Dev Simplified, 2026-07-07)
- [x] [video] [Backend web development - a complete overview](https://www.youtube.com/watch?v=XBu54nfzxAQ) (Youtube, Backend web development - a complete overview, 2026-07-07)
- [x] [article] [What is backend? A comprehensive intro to server-side development](https://alokai.com/blog/what-is-backend)
- [article] [What is Back-End Architecture?](https://www.codecademy.com/article/what-is-back-end-architecture)

## 互联网是如何工作的

互联网是一个由相互连接的计算机组成的全球网络，这些计算机使用 TCP/IP 协议进行通信。请求首先通过互联网服务提供商传输到域名解析服务器，进行从域名到 IP 地址的转换，然后通过路由器在网络中路由，最终到达目标服务器。这使得全球范围内的通信能够更加灵活且分散化。

- [video] [How does the internet work? (Full Course)](https://www.youtube.com/watch?v=zN8YNNHcaZc) (Youtube)
- [x] [article] [How does the internet work?](https://roadmap.sh/guides/what-is-internet) (roadmap.sh, Kamran Ahmed)
- [x] [article] [How does the Internet Work?](https://cs.fyi/guide/how-does-internet-work)
- [article] [The Internet Explained](https://www.vox.com/2014/6/16/18076282/the-internet)


## 什么是 HTTP

HTTP（HyperText Transfer Protocol）是 Web 中客户端和服务器交换数据的应用层协议。浏览器、移动应用或其他客户端会向服务器发送请求，服务器再返回响应；请求方法、状态码、请求头、响应头和 HTTPS 都是理解 Web 通信时必须掌握的基础。

- [video, course] [Full HTTP Networking Course](https://www.youtube.com/watch?v=2JYT5f2isg4)
- [video] [HTTP/1 to HTTP/2 to HTTP/3](https://www.youtube.com/watch?v=a-sBfyiXysI)
- [x] [article] [What is HTTP?](https://www.cloudflare.com/en-gb/learning/ddos/glossary/hypertext-transfer-protocol-http/)
- [article] [HTTP/3 From A To Z: Core Concepts](https://www.smashingmagazine.com/2021/08/http3-core-concepts-part1/)

## 什么是域名

域名是人类更容易记忆的网站地址，例如 `roadmap.sh`。它把难以直接记忆的 IP 地址包装成可读名称，并通过顶级域名、子域名、注册商和 DNS 等机制与真实服务器地址关联起来，让用户可以通过浏览器访问对应网站。

- [x] [article] [What is a Domain Name?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name)
- [article] [What is a Domain Name? | Domain name vs. URL](https://www.cloudflare.com/en-gb/learning/dns/glossary/what-is-a-domain-name/)
- [video] [A Beginners Guide to How Domain Names Work](https://www.youtube.com/watch?v=Y4cRx19nhJk)
- [video] [Everything You Need to Know About Domain Names](https://www.youtube.com/watch?v=qO5qcQgiNX4)

## 主机

主机服务提供服务器空间和资源，用于在互联网上存储和传递网站。类型包括共享主机、VPS、专用主机和具有可扩展资源的云主机。服务包括基础设施、域名注册、安全和技术支持，以确保网站的可靠可用性。

- [article] [What is the difference between Webpage, Website, Web server, and search engine?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/Pages_sites_servers_and_search_engines)
- [article] [What is a web server?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_web_server)
- [video] [What is Web Hosting and How Does It Work?](https://www.youtube.com/watch?v=H8oAvyqQwew)
- [video] [Different Types of Web Hosting Explained](https://www.youtube.com/watch?v=AXVZYzw8geg)

## DNS 及其工作原理

DNS（Domain Name System）可以理解为互联网的“电话簿”：浏览器拿到域名后，需要通过 DNS 解析找到对应的 IP 地址。这个过程通常会经过递归解析器、根域名服务器、顶级域名服务器和权威域名服务器，并受到 DNS 记录、缓存、TTL 和解析传播时间的影响。

- [article] [Everything You Need to Know About DNS](https://cs.fyi/guide/everything-you-need-to-know-about-dns)
- [article] [What is DNS?](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/)
- [article] [How DNS works (comic)](https://howdns.works/)
- [video] [DNS and How does it Work?](https://www.youtube.com/watch?v=Wj0od2ag5sk)

## 浏览器及其工作原理

浏览器负责把用户输入的 URL 转换成实际的网络请求，获取 HTML、CSS、JavaScript、图片等资源，然后解析、渲染并展示页面。理解浏览器如何发起请求、构建页面、执行脚本、缓存数据以及提供开发者工具，有助于后端开发者更好地排查接口、性能和跨端协作问题。

- [article] [How Browsers Work](https://www.ramotion.com/blog/what-is-web-browser/)
- [article] [Populating the Page: How Browsers Work](https://developer.mozilla.org/en-US/docs/Web/Performance/How_browsers_work)
- [video] [How Do Web Browsers Work?](https://www.youtube.com/watch?v=5rLFYtXHo9s)