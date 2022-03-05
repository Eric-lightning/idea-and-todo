# idea and todo note.
My Idea and todo notepad.

> This idea is PUBLIC DOMAIN.
> But, I want to know your solution for interesting
> ( I don't claim any right to it, and I don't make any teasers about it. )

## List

- [www.md](www.md) ... About World Wide Web
- [Life.md](Life.md) ... How do improve My Life Quality?


## No Sorted

## Product

### Windows Explorer Integration like Cloud Application with Linux SFTP Server.
  
  - 2Socket:
    - [1]. Client Sender( `local$ sftp server.example.com`)
    - [2]. Server Sender( `local$ ssh -R $REMOTE_PORT:localhost:22 server.example.com` and service run: `server$ sftp localhost:$REMOTE_PORT`)
    - TODO: about [2]: how to get Modification Event without root permission...
  - See Virtual Files(Not Downloaded) like Cloudware (e.g. OneDrive, MEGA.nz, Google Drive etc...)
  - Realtime Sync.
  - Small Dependency: ssh and bash

### Smart Voice Recorder.
  
  - First, Recording your voices.
  - Second, Learning Your Voices, and transcription to text-file.
  - Third, Identify voiced and generate a file in the Minutes format!

### Simple WYSIWYG Editor.
  
  - file: ZIP FILE include PureHTML and Git Version Management.
    - Complementation with JSON when it can not be represented by `<meta>`
    - append tag id and class from GUI with Style Sheet.
    - and Include CSS managed with pixel adapted dpi.
    - FILE COPY -> `git clone`
    - CONFLICT SAME FILE NAME -> `git merge`
    - Manage Version without Cloudware like OneDrive.
  - Size Pixel adapted by dpi.
    - example: Selected A4 Paper, DPI: 300px, Papersize: 3508×2480
    - or, managed by `pt`, `px`?
  - Printing adapted by dpi(**For official documents in strict format**)
  - Dynamic Document/Component via Javascript, and Extensions.
  - for Document.
    - GoalX: Notepad App
    - Goal0: Prototype HTML Editor(no Version Manage, No CSS)
    - Goal1: CSS Implematation
    - Goal2: formality Document with any styles!
    - Goal3: Simple Version Manage(no Fork, no Merge)
    - Goal4: Greatful Version Manage(Fork/Merge Support)
    - Goal5: Use Non-Enginner, alternative Ms Word Editor, Open Standard Editor

### Wiki Helper API (WHAPI)
  
  - Pure Wiki Server Side API
  - CRUD+Meta
    - CREATE PAGE ... `PUT /path/to/endpoint`
    - READ PAGE ... `GET /path/to/endpoint?type=[html|pdf|md]`
    - UPDATE ... `PUT /path/to/endpoint`
    - DELETE ... `DELETE /path/to/endpoint`
    - Manage Meta Data, Extension ... `POST /request/path/name` with JSON.
  - Managed/Insipred Git(One Server One Repository, repository-name: FQDN?)
    - Req: `PUT X-Update-Type: Draft` --> `checkout -b [username]` ---> Save Draft at `[username]` branch.
    - Req: `PUT X-Update-Type: Commit` ---> Save Docs with Commit Mesg at `[username]` branch.
    - Req: `POST /version-control/merge` ---> merge to another branch(e.g. public, main, community_name)
    - Req: `POST /version-control/clone` ---> clone to my server.
    - Req: `POST /version-control/request-pull` ---> req pull.
    - Req: `POST /version-control/pull` ---> pull to upper stream.
    - Req: `POST /version-control/push` ---> push from down stream.
    - Req: `POST /search` with keyword and page ---> return result JSON.
    - Req: `POST /info/latest-updates`, `POST /
  - Linking Other WHAPI Server
    - GET Search Index Difference Data `POST /public-data/indexes`
    - GET Another Server Information via DHT?, RoutingTable?:  `POST /public-data/servers`
      - IRC/Matrix Integration: Discussion between servers.

#### WHAPI Frontend Implemantaion
  
  - Search Communicaton
  - Dynamic Applied Style Sheet.(dark/light, Page)
  - Editor

### Cafe Sign-in with NFC Tips
  
  - Why cafes using Captive Portal?
  - Autogenerate WPA3-PASSWORD day by day.
  - Autowrite NFC Tag of countertop.
  - User need to entry when accouning.

### Emergency(Fire and Earthquake) Alarm, Announcement broadcast Bypass to PC or Smartphone
  
  - In recent years, the number of people listening to music with earphones has been increasing.
  - Risk of not being aware of important notifications such as building fires, station announcements, etc.
  - Therefore, I would like to create an application that bypasses station broadcasts and emergency sirens for building fires and so on.


## SNS

- Arbitration System Using Sentiment Judgment, Argument Judgment, and Gathering of Opinions by Natural Language Analysis, Discussion SNS Platform.
- Automatic Information Source Acquisition System on SNS

## Third-Party Services

- Twitter Client liked Nostalgic PC communication services
  - Simple Text-Only realtime Terminal Viewer via ssh or local
  - vim-binding post editor
  - save tweets and search by regex
  - save tweets cron daemon(for offline viewing)

## Analyze

- 全国紙５社HPをスクレイピングし，Macabによる形態素解析，単語出現頻度を見て傾向を探る．あとPresident Onlineとか，Gigazineとかギズモード，デイリーガジェットなど見たい．

## How-to

- QiitaのタイトルをGithub Profile Pagesに貼り付ける方法

## Work efficiency

- MyPage
  - Two Col, right pain is my memorandum, left pain is today schedule or todo.
  - Simple Autentication(Digest on SSL)
  - edit md, output simple html.
  
- Calendar Application
  - add Schedule from Template(e.g. Pattern of time going to office)
  - Easy Copy&Paste of Schedule


## Utility

- `mdrandr` .. markdown rendering tool
  - fast
  - **expandability(mdrandr subpackage manager for third-party tool)**
  - calm down usage(good-old unix command usage)
  - support stdin(via pipe)
  - (limited CSS)
  - todo: fork from [github/cmark-gfm](https://github.com/github/cmark-gfm)

- `ipseq` ... output ip addr like `seq` command from CIDR, NetworkAddress/Mask, File... impl. using GoLang.
  - e.g. `ipseq 172.22.1.0/24 | fping -f -` 
  - http://github.com/anya-tokugawa/ipseq-cli

- `termrec` ... alternative `script` command. terminal record to Simple readable unix plain text liked CSV, JSON, and so on.
  - and modern style command
  - result output uuid.stdout and uuid.stderr to file by exec
  - timestamp and command list.
 
 ```
 2021-11-12 13:11:03 ls -l
 2021-11-12 13:11:19 cd hoge/bar
 ```

## Learning/Interesting.

### Language

- English(aimed to TOEIC 800+)
- German(interesting)
- Russian(interesting)

### Prog. Lang.

- Rust
- Perl
- Go
