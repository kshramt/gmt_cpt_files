# GMT cpt files
## Usage
Locate `*.cpt` into `~/.gmt`.

    mkdir ~/.gmt
    cp gmt_cpt_files/*.cpt ~/.gmt
    cd work
    makecpt -Cglobe_light T0/1/0.1 -Z > globe_light.cpt
