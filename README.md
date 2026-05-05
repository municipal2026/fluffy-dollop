@echo off

mkdir garage_project
cd garage_project

mkdir vehicles
mkdir orders
mkdir assets

echo ^<?php $conn = new mysqli("localhost","root","","garage"); ?^> > db.php

echo ^<h2^>Dashboard^</h2^> > dashboard.php

echo ^<form method="POST"^>^<input name="username"^>^<input name="password"^>^<button^>Login^</button^>^</form^> > index.php

echo CREATE DATABASE garage; > database.sql

echo Done!
pause
