message("\n** HELLO AND WELCOME TO THIS PROJECT! **")
proj.root <- rprojroot::find_rstudio_root_file()

lib.loc <- "packages"
lib.loc <- paste(proj.root, lib.loc, sep="/")

# file.exists("/homedirs18/sghms/bms/shares/bdib")
# lib.loc <- "/homedirs18/sghms/bms/shares/bdib/BDiB_2017_18/Session_07/Session_07_R_Packages"
# file.exists(lib.loc)
# styles.loc <- "styles"

for (foldr in c(lib.loc, proj.root)) {
  if(!file.exists(foldr)) {
    message(paste("Error in .Rprofile. This folder does not exist:", foldr))
  }
}
rm(foldr)

stopifnot(file.exists(lib.loc))
# .libPaths(c("~/R/Rlibs/_packages_r3.3", lib.loc))
.libPaths(lib.loc)
.libPaths()
# [1] "/homes/homedirs26/sghms/bms/users/anohturf/_BDiB/BDiB_2017_18/Session_07/bdib_2018/packages"
# [2] "/usr/lib64/R/library"                                                                       
# [3] "/usr/share/R/library" 

library(rmarkdown, lib.loc=lib.loc)

# message(paste0("\nProject-specific packages are stored in: ", lib.loc))
# message(paste(".Rprofile sets a variable (2) - 'styles.loc', whose value is:", styles.loc))
# message(paste(".Rprofile sets a variable (3) - 'manu.loc', whose value is:", manu.loc))
# message(paste(".Rprofile sets a variable (4) - 'proj.root', whose value is:", proj.root))
# message(paste(".Rprofile sets a variable (1) - 'lib.loc', whose value is:", lib.loc))
# message("To install packages: install.packages('dplyr', lib=lib.loc)")
# message("To load packages (example): library(dplyr, lib.loc=paste(proj.root))\n")

