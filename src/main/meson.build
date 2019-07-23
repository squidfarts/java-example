###################################################################################
#                                                                                 #
# NAME: src/main/meson.build                                                      #
#                                                                                 #
# AUTHOR: Michael Brockus.                                                        #
#                                                                                 #
# CONTACT: <mailto:michael@squidfarts.com>                                        #
#                                                                                 #
# NOTICES:                                                                        #
#                                                                                 #
# License: MIT                                                                    #
#                                                                                 #
###################################################################################



exe_jar = jar('exe', join_paths('com', 'squidfarts', 'Main.java').
    main_class : 'com.squidfarts.idea.Main',
    install : true)

test('test jar file', exe_jar)