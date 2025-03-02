name: Avica

on:
  workflow_dispatch:

jobs:
  build:
    name: Start Building...
    runs-on: windows-latest
    timeout-minutes: 360

    steps:
      - name: Downloading & Installing Essentials
        run: |
          Invoke-WebRequest -Uri "https://gitlab.com/raposabrty/pcrdp/-/raw/main/Downloads.bat" -OutFile "Downloads.bat"
          cmd /c Downloads.bat
      - name: Show Website
