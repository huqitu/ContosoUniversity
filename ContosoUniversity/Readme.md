﻿创建ContosoUniversity项目的步骤

一、创建 mvc core新项目<br/>
二、项目名称：ContosoUniversity<br/>
三、增加菜单项，在Views/Shared/_Layout.cshtml的菜单中增加如下代码
<li class="nav-item">
    <a class="nav-link text-dark" asp-area="" asp-controller="Home" asp-action="About">About</a>
</li>
<li class="nav-item">
    <a class="nav-link text-dark" asp-area="" asp-controller="Students" asp-action="Index">学生</a>
</li>
<li class="nav-item">
    <a class="nav-link text-dark" asp-area="" asp-controller="Courses" asp-action="Index">课程</a>
</li>
<li class="nav-item">
    <a class="nav-link text-dark" asp-area="" asp-controller="Instructors" asp-action="Index">讲师</a>
</li>
<li class="nav-item">
    <a class="nav-link text-dark" asp-area="" asp-controller="Departments" asp-action="Index">部门</a>
</li>


