# Copyright (C) 2007-2012 LuaDist.
# Created by Peter Drahoš
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

project ( batteries NONE )
cmake_minimum_required ( VERSION 2.8 )
include ( cmake/dist.cmake )

# Just install the README
install_doc ( README.md )
