# SSH Setup (Termux to PC)

## Objective
Connect my Android (Termux) to my PC using SSH.

## Steps
1. Installed SSH on PC
2. Found IP using `ip a`
3. Started SSH:
   sudo systemctl start ssh
4. Connected:
   ssh username@192.168.x.x

## Problem
Connection failed at first because SSH service was not running.

## Solution
Started SSH service and retried.

## What I learned
- How SSH works
- Port 22 basics
- Client-server connection
