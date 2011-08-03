project(VisPipelines NONE)

cmake_minimum_required(VERSION 2.8)

include(UseLATEX.cmake)

set(images
  images/SimplePipeline.pdf
  images/BranchingPipeline.pdf
  images/BranchingPipelineResult.png
  images/UpdateInformation.pdf
  images/UpdateRegion.pdf
  images/UpdateData.pdf
  )

add_latex_document(VisPipelines.tex
  BIBFILES VisPipelines.bib
  IMAGES ${images}
  )
