<p align="center">
    <img src="s.jpg" alt="image">
</p>

## 🧾 About Me

Backend / distributed systems / web. I`m also interested in low-lavel and I like to create wrappers to improve expierence.

```assembly
section .data
  name db "Artemiy Wanchugov", 0xA
  age db 16
  msg db "Viva Argentina"
  message_len equ $ - msg

section .text
  global _start

_start:
  mov rax, 1
  mov rdi, 1
  mov rsi, msg
  mov rdx, message_len
  syscall

_end:
  mov rax, 60
  syscall
```

<br>

## 📁 My Projects

<table>
  <tr>
    <td valign="top">
      <b><a href="https://github.com/KoP3YkA/ModularORM">ModularORM</a></b><br/>
      Lightweight and modular ORM for TypeScript with built-in query builder.<br/>
      <sub><code>TypeScript</code> • <code>MySQL</code> • <code>npm</code></sub>
    </td>
  </tr>
  
  <tr>
    <td valign="top">
      <b><a href="https://github.com/KoP3YkA/Time">Time</a></b><br/>
      Library focused on time formatting and convenient manipulation<br/>
      <sub><code>TypeScript</code> • <code>Datetime</code> • <code>npm</code></sub>
    </td>
  </tr>
  
  <tr>
    <td valign="top">
      <b><a href="https://github.com/KoP3YkA/FineHTTP">FineHTTP</a></b><br/>
      Simple library that will help you type standard fetch and automate some actions.<br/>
      <sub><code>TypeScript</code> • <code>fetch</code> • <code>npm</code></sub>
    </td>
  </tr>

  
  <tr>
    <td valign="top">
      <b><a href="https://github.com/KoP3YkA/ctest">cTEST</a></b><br/>
      This is a simple and lightweight C library that will allow you to test your application and see the test results right in the console.<br/>
      <sub><code>C</code> • <code>tests</code> • <code>lightweight</code></sub>
    </td>
  </tr>

  
  <tr>
    <td valign="top">
      <b><a href="https://github.com/KoP3YkA/docker-cli-tool">DockerCLI</a></b><br/>
      A console utility that allows you to easily create Dockerfile and docker-compose with a single command.<br/>
      <sub><code>C</code> • <code>cli</code> • <code>docker</code></sub>
    </td>
  </tr>

  <tr>
    <td valign="top">
      <b><a href="https://github.com/KoP3YkA/mysql-c-driver">MySQL C Driver</a></b><br/>
      This is an unfinished project that was supposed to be a mysql driver in C, with which you could send SQL queries through a single function, directly in C.<br/>
      <sub><code>C</code> • <code>mysql</code> • <code>driver</code></sub>
    </td>
  </tr>
</table>

<br>

<br>

## ⚙️ My Stack
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,js,nodejs,git,github,gitlab,discordjs,mysql,sqlite,nestjs,redis,npm,jest,java,python,docker,c" />
  </a>
</p>


