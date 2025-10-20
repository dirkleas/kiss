# kiss - keep it simple support (stack)

remote support is always tricky -- it's always hard to listen to the person providing support, follow along with their instructions (often doing new things, riddled with jargon, new concepts, etc.), learn, and still take notes. it's like juggling cats -- here's an approach that attempts to reduce the friction a bit, where you can just watch and learn!

this **kiss** model is based on a few free, practical tools that help with **simple** remote support...

**support paticipants:**

1. **🙋‍♂️ supportee** - person **requesting** and **receiving** technical support
1. **🤓 supporter** - person **providing** technical support

## windows support apps

the following secure, free apps are used for **windows 11+** support:

1. [teamviewer](https://www.teamviewer.com/en-us/) (free version) - secure remote control app, install on both **🤓 supporter** and **🙋‍♂️ supportee** computers and mobile phones
1. [signal](https://signal.org/) - secure text, voice, and video conferencing, install on both **🤓 supporter** and **🙋‍♂️ supportee** computers and mobile phones and set up private chat
1. [keyviz](https://github.com/mulaRahul/keyviz) - onscreen keyboard visualizer, install latest alpha release on **🙋‍♂️ supportee** computer
1. [mouse pointer highlight](https://apps.microsoft.com/detail/9p7sb9s4rq7z?hl=en-US&gl=US) - onscreen mouse cursor highlighter, install on **🙋‍♂️ supportee** computer

## kiss support workflow

getting support is easy...

1. **🙋‍♂️ supportee:** reach out via **signal** with a text requesting support and what you need or are having issues with
1. **🤓 supporter:** once support time is confirmed, **🙋‍♂️ supportee** receive text voice call via **signal** from **🤓 supporter**
1. **🙋‍♂️ supportee:** start **teamviewer** and share your new password via **signal** text during during voice call
1. **🤓 supporter:** you'll be contacted via **teamviewer** and support begins
    1. **🤓 supporter:** run **mouse pointer highlight** and optionally **keyvis** apps
    1. **🤓 supporter:** by default, manage most keyboard and mouse activity and provide detailed walkthrough of what's happening
    1. **🙋‍♂️ supportee:** provide any required credentials as needed based on support requirements

## roadmap

here's some upcoming possibilities:

1. command line interface (cli) with even more powerful features
1. record/edit support engagements with [obs](https://obsproject.com/) and post along with summaries, tags, etc. in searchable website with natural language interface for live q&a
1. optimize obs stack workflow with live-triggered markers for automated editing, including automatic removal of live research, off-topic tracks, and misspeaks, etc. via embedded markers
1. provide apps list for **macos**, **linux**, etc.
