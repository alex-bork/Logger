# Logger
Simple Logger Application that can be used via command line in order to store log information into a file.
</br>
</br>
Has the following parameter:
</br>
| Parameter | Value | Obligatory | Description |
| --- | --- | --- | --- |
| -m (--message) | string | yes | Message that should be logged
| -f (--file) | string | no | Must contain the file path and name of a custom log file
| -n (--new) | - | no | Flag that defines if a log file should be created, if not exists
| -t (--type) | string(1) | no | Message type: i (Info), s (Success) , e (Error) , w (Warning)
| -l (--level) | integer | no | Level of text indentation in the file |

## Versions

### 1.0.0
Initial Verison

### 1.1.0
- deleted unnessesary message
