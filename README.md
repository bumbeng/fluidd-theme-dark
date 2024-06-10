## fluidd-theme-dark

![Screenshot 2024-06-10 201727](https://github.com/bumbeng/fluidd-theme-dark/assets/111509593/2b304b0e-2fcb-4fe5-a4eb-0ec578d7e769)


## How to install
- create a folder called .fluidd-theme in config section
- copy the downloaded files into this folder
- reload browser

## Logo change
- name an picture to logo.png
- put this image to .fluidd-theme
- insert these lines with `!! your url !!` of the logo.png file into custom.css

      .logo-wrapper {
            display: none !important;
        }
        .theme--dark .toolbar-logo {
            background-image: url(http://mainsailos.local/server/files/config/.fluidd-theme/sidebar-logo.png) !important;
            background-size: 48px !important;
            background-repeat: no-repeat !important;
            background-position: center !important;
        }
