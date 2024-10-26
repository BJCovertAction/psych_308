# Activate virtual environment

# Construct path to default profile file
home_dir = file.path(path.expand("~"))
def_profile_path = home_dir
def_profile_filename = ".Rprofile"
def_profile_file = file.path(def_profile_path, def_profile_filename)

# If it exists, source general Rprofile for machine
if(file.exists(def_profile_file)){
    source(def_profile_file)
}

