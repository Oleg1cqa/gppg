## Welcome to the adaptation of GPPG for dotnet core.

Project based on [Gardens Point Parser Generator](http://gppg.codeplex.com/)

#### How to use
For use in dotnet core projects you need add next text in project.json

`  "tools": {
    "StarodubOleg.GPPG" : "0.1.0-alpha1-2"
  },`

`  "scripts": {
    "precompile": [ "dotnet gppg /gplex /nolines %project:Directory%/gppg.y" ]
  }`