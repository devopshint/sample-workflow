name: shell commands

on: [push]

jobs: 
  run-shell-commands:
    runs-on: ubuntu-latest
    steps: 
      - name: string
        run: echo "Welcome to Devopshint!!"
      - name: multiline script
        run: |
          node -v
          npm -v
      - name: python command
        run: |
          import platform
          print(platform.processor())
        shell: python

  run-windows-command:
    runs-on: windows-latest
    steps:
      - name: Directort Powershell
        run: Get-Location
      - name: Directort Bash
        run: pwd
        shell: bash
