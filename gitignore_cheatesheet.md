# Gitignore Cheatsheet
| patterns | definations | example
| `*.a` | Ignore all .a files | `*.a`|
| `!lib.a` | But do track lib.a, even though you're ignoring .a files above | `!lib.a`|
| `/TODO` | Only ignore the TODO file in the current directory, not subdir/TODO | `/TODO`|
| `build/` | Ignore all files in any directory named build | `build/`|
| `doc/*.txt` | Ignore doc/notes.txt, but not doc/server/arch.txt | `doc/*.txt`|
| `doc/**/*.pdf` | Ignore all .pdf files in the doc/ directory and any of its subdirectories | `doc/**/*.pdf`|
| `*.[oa]` | Ignore all .o and .a files | `*.[oa]`|
| `foo/` | Ignore the foo/ directory | `foo/`|
| `foo/**/bar` | Ignore bar in the foo/ directory and any of its subdirectories | `foo/**/bar`|
| `foo/*/bar` | Ignore bar two levels below foo/ directory | `foo/*/bar`|
| `!foo/bar/baz` | Do not ignore foo/bar/baz | `!foo/bar/baz`|
| `*.log` | Ignore all .log files in the working directory | `*.log`|
| `config.php` | Ignore config.php in the working directory, but not subdir/config.php | `config.php`|
| `config/` | Ignore the config/ directory in the working directory, but not subdir/config/ | `config/`|
| `/config` | Ignore the config/ directory two levels below the working directory, but not two levels below subdir/ | `/config`|
| `**/config` | Ignore config/ directory in any subdirectory | `**/config`|