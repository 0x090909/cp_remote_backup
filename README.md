# cPanel Remote Backup Mounter

## Problem

When managing the WHM infrastructure you often find yourself dealing with backups, and let's say you want to backup your server daily retaining 7 days of past backups, guess the problem.

Exactly, SPACE.

What a normal person whould do is to have an external NAS and dump the backups there, without storing them on the actual server.

Now let's say you manage 100 accounts and an earthquake destroyes your files, keeping in mind that every backup is about 1 TB of data, you want to restore the files you backedup as soon as possible right?

## Solution


Without the need to copy manually the files from the NAS to the server, this app lets you mount the remote location locally in the server, then you can restore your backup as if it was already copied in the server.

