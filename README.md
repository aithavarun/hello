<%@ Page Language="C#" AutoEventWireup="true" CodeBehind="WebForm1.aspx.cs" Inherits="now.WebForm1" %>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
    <title></title>
    <style type="text/css">
        .auto-style1 {
            color: #000066;
        }
    </style>
</head>
<body style="text-align: left">
    <form id="form1" runat="server">
        <div style="text-align: center" class="auto-style1">
            <strong>LOGIN2 FORM</strong></div>
        <p>
            USERNAME&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <asp:TextBox ID="TextBoxes1" runat="server"></asp:TextBox>
        </p>
        <p>
            PASSWORD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <asp:TextBox ID="TextBoxes2" runat="server"></asp:TextBox>
        </p>
    <p>
        <asp:Button ID="Button1" runat="server" Text="login" />
        </p>
    </form>
    </body>
</html>
