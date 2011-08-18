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
  images/TaskParallel0.pdf
  images/TaskParallel1.pdf
  images/TaskParallel2.pdf
  images/PipelineParallel0.pdf
  images/PipelineParallel1.pdf
  images/PipelineParallel2.pdf
  images/PipelineParallel3.pdf
  images/DataParallel.pdf
  images/PhotoMoreland.jpg
  )

add_latex_document(VisPipelines.tex
  BIBFILES VisPipelines.bib
  IMAGES ${images}
  )
