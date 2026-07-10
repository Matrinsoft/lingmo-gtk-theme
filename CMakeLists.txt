cmake_minimum_required(VERSION 3.20)
project(lingmo-gtk-theme VERSION 1.0.0 DESCRIPTION "Lingmo GTK Theme" LANGUAGES NONE)
install(DIRECTORY Lingmo DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Lingmo-light DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Lingmo-dark DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
    
