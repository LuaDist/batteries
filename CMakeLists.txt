# Copyright (C) 2011 LuaDist.
# Created by Peter Drahoš
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

project ( batteries NONE )
cmake_minimum_required ( VERSION 2.6 )

# Just a metapackage, message the user
add_custom_target ( install
  COMMAND echo "This is a meta-package for the LuaForWindows collection of Lua modules."
)
