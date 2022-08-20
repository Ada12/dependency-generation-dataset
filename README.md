## Dataset Decription

- `/dependency` directory contains all dependency information for each project.
  - `/dependency/project-libs.json`are Maven projects collected from library.io (the filter criteria is the project possesses at least 10 dependency libraries), and all dependency libraries are identified by `<groupdId>:<artifactId>`。
  - `/dependency/lib_infos.csv` contains all dependency tags and description deriving from the Maven central repository in  `project-libs.json` . Multiple tags for a dependency are splited by  `=` .

