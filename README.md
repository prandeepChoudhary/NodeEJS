
//project create commands
npm init -y
npm i express ejs
mkdir views; touch index.js views/index.ejs

-----ejs syntex------------------------------------------

<%= variable %>             --JS Output
<% Console.log("hello") %>  --JS  Execute
<%- <h1>Hello</h1> %>       --Render HTML
<%% %%>                     --Show <% or %>
<%# This is a Comment %>    --Stop Execute
<%- include("header.js") %> --Insert another EJS file
