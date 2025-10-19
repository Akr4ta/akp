# akp
A wrapper for pacman, yay and flatpak

akp aims to:
* Centralize the use of the three package managers
* Offer the installation of optional dependencies when installing packages
* Present Arch package search output in a table format
* Command redesign

# commands
akp -Ud                Update arch, aur and flatpak repositories
akp -U                 Update Arch
akp -S   [package(s)]  Search Arch package (installed packages will be printed in green)
akp -I   <package(s)>  Install Arch package(s)
akp -R   <package(s)>  Remove Arch/AUR package(s)
akp -Rd  <package(s)>  Remove Arch/AUR package(s), its dependencies and all the packages that depend on the target package(s)
akp -Qi  [package(s)]  Query local package information
akp -Qir [package(s)]  Query package information in the Arch repositories
 
akp -Ua                Update AUR
akp -Sa  [package(s)]  Search AUR package
akp -Ia  <package(s)>  Install AUR package(s)
akp -Qai [package(s)]  Query package information in the AUR
akp -Qal               Query list installed AUR packages
 
akp -Uf                Update Flatpak
akp -Sf  <package(s)>  Search Flatpak package
akp -If  <package(s)>  Install Flatpak package(s) from flathub
akp -Rf  <package(s)>  Remove Flatpak package(s)
akp -Qfi <package(s)>  Query Flatpak package information
akp -Qfl               Query list installed Flatpak packages
 
akp -h                  Shows help page
