add_subdirectory(whale)
simcenter_add_python_script(SCRIPT femUQ.py)
simcenter_add_python_script(SCRIPT PBE.py)
simcenter_add_python_script(SCRIPT "PBE_workflow.py")
simcenter_add_python_script(SCRIPT "R2DTool_workflow.py")
simcenter_add_python_script(SCRIPT RegionalEarthquakeSimulation.py)
simcenter_add_python_script(SCRIPT WorkflowUtils.py)
simcenter_add_file(NAME WorkflowApplications.json)
