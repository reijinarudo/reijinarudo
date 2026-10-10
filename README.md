# Dr. Reginald Finley, Sr.

Educator, scientist, and builder. I teach anatomy and physiology, doctoral statistics, and scientific literacy at Franklin University, design industrial automation training for Siemens, and run the Finley Robotics Initiative, a Georgia nonprofit that puts robots in front of students. The projects below are tools I built for my own work and then cleaned up so anyone can run them. Every repository has a README that explains setup from scratch, an MIT license, and credit to the upstream projects it builds on.

Portfolio and contact: [drreginaldfinley.com](https://drreginaldfinley.com)

## Robotics

| Project | What it does |
|---|---|
| [reachy-aiden](https://github.com/reijinarudo/reachy-aiden) | Turns a Reachy Mini Wireless into a voice companion with its own persona, long-term memory, and extra tools, running on the robot plus cloud voice models. Switch the backend between Hugging Face, OpenAI, and Gemini with one command; a boot-time guard restores the changes after Pollen updates. [Demo video](https://youtu.be/L9EhXOoIOt4). |
| [reachy-rose](https://github.com/reijinarudo/reachy-rose) | A Reachy Mini robot whose speech recognition, language model, and voice all run on a Mac mini at home, with no cloud service in the conversation. Includes a guide to what worked and what failed while getting a local model to run at conversational speed. [Demo video](https://youtu.be/Es0EJx5NEdE). |

Aiden and Rose are siblings: the same robot, one on cloud voice models and one fully local.

## Voice assistants

| Project | What it does |
|---|---|
| [project-aion](https://github.com/reijinarudo/project-aion) | A talking 3D desktop avatar for Windows. OpenAI realtime voice, lip sync through VMagicMirror, Google Calendar by voice, and a plain-text memory file. Comes with a guide to building your own character. [Demo video](https://youtu.be/dExOrEA55wY). |
| [instructional-assistant](https://github.com/reijinarudo/instructional-assistant) | A one-button Windows app that listens to a live class and answers spoken questions out loud, so an instructor can get a short answer mid-lecture without stopping to type. Ships with two teaching profiles. |
| [local-grading-assistant](https://github.com/reijinarudo/local-grading-assistant) | A private AI assistant and grading toolkit that runs on one computer you own. Built so student work never leaves local hardware. |

## Pipelines and tools

| Project | What it does |
|---|---|
| [audio-to-youtube-pipeline](https://github.com/reijinarudo/audio-to-youtube-pipeline) | Turns a folder of audio recordings into finished YouTube videos (captioned background, waveform, thumbnail, generated title and description) and uploads them on a schedule. Built to publish a 500-episode radio archive. |
| [job-search-pipeline](https://github.com/reijinarudo/job-search-pipeline) | Reads employers' applicant tracking systems directly each night, screens postings against rules you write once, and emails a digest. Every judgement the filter makes is listed so you can overrule it. |
| [gedbook](https://github.com/reijinarudo/gedbook) | Drafts a print-ready family history book as a PDF from a GEDCOM export and a folder of photos. Built while writing a two-volume history from a tree of about 8,000 people. |

## Websites

| Site | Repository |
|---|---|
| [GeorgiaScience.org](https://georgiascience.org), news and resources on science education in Georgia | [GeorgiaScience](https://github.com/reijinarudo/GeorgiaScience) |
| [Access to Robotics](https://accesstorobotics.org), the Finley Robotics Initiative | [accesstorobotics](https://github.com/reijinarudo/accesstorobotics) |
| [drreginaldfinley.com](https://drreginaldfinley.com), portfolio | [Portfolio](https://github.com/reijinarudo/Portfolio) |

## How these were built

Each project started as a working setup on my own machines and was rewritten for release: credentials moved to environment variables, local paths to example config files, and personal data out of the repository entirely. Where a project builds on someone else's open-source work, the upstream license is kept and the README names the original authors and describes exactly what I changed.

Questions, bug reports, and pull requests are welcome on any repository.
