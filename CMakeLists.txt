project(VisPipelines NONE)

cmake_minimum_required(VERSION 2.8)

include(UseLATEX.cmake)

set(images
  )

add_latex_document(VisPipelines.tex
  BIBFILES VisPipelines.bib
  IMAGES ${images}
  )
