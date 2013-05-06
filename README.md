tasks
=====

Simple Task Manager

Usage
-----

usage: tasks [-h] [--verbose [verbose]] [--task_cfg FILENAME]
             [--task_file FILENAME] [-p PROJECT] [-o OWNER]
             [-s {open,doing,close}] [-t TITLE] [-d DESCRIPTION] [-c COMMENT]
             [-f FIELD=VALUE] [--fields-only]
             ACTION [TASKID [TASKID ...]]

Text Task System

positional arguments:
  ACTION                Action to be done. Choices mk, up, rm, ls, cat
  TASKID                Task ID.

optional arguments:
  -h, --help            show this help message and exit
  --verbose [verbose], -v [verbose]
                        Levels debug, info, warning, error, critical. Default
                        info. Const debug
  --task_cfg FILENAME   Task config. Default ~/.tasks.cfg.
  --task_file FILENAME  Task file. Default tasks.txt.
  -p PROJECT, --project PROJECT
                        Task project.
  -o OWNER, --owner OWNER
                        Task owner.
  -s {open,doing,close}, --status {open,doing,close}
                        Task status. Choices open, doing, close.
  -t TITLE, --title TITLE
                        Task title.
  -d DESCRIPTION, --description DESCRIPTION
                        Task description.
  -c COMMENT, --comment COMMENT
                        Add comment to task.
  -f FIELD=VALUE, --field FIELD=VALUE
                        Add any field as task field.
  --fields-only         Used by rm action. Delete fields only instead of the
                        task. Default False.

