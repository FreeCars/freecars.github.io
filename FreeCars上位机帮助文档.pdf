<!--#include file="varify.asp"-->
<!--#include file="business.asp"-->
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>玉兰苑租房租客信息系统</title>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <link rel="stylesheet" type="text/css" href="Scripts/common.css" />
    <script src="Scripts/jquery-1.4.1.js" type="text/javascript"></script>
    <%=Ref("Scripts/page_ref.js") %>
</head>
<body>
    <div class="myTitle">
        <!--这里是网页正上方，正中央-->
        租房信息查询系统<%if Session("Role")="admin" then %><span><a href="javascript:void(0);" class="btn" onclick="oPage.logOut()">[退出登陆]</a></span><%end if %>
    </div>
    <%if Session("login")<>"true" then Response.Redirect("default.aspx") %>
    <div class="MainContent">
        <div class="NaviWindow">
            <a class="LinkButton" href="checkfee.asp" target="frmDisplay">费用查询</a>
            <a class="LinkButton" href="AboutRentor.htm" target="frmDisplay">房东信息</a>
            <a class="LinkButton" href="http://www.baidu.com/" target="frmDisplay">百度</a>
        </div>
        <div class="ContWindow">
            <iframe src="" height="100%" width="100%" scrolling="auto" id="frmDisplay" frameborder="0"></iframe>
        </div>
    </div>
</body>
</html>