simcenter_add_executable(NAME extractEDP
                         FILES extractEDP.cpp
                         DEPENDS CONAN_PKG::jansson)
simcenter_add_executable(NAME postprocessDakota
                         FILES postprocessDakota.cpp
                         DEPENDS CONAN_PKG::jansson)
simcenter_add_executable(NAME preprocessDakota
                         FILES preprocessDakota.cpp dakotaProcedures.cpp
                         DEPENDS CONAN_PKG::jansson)
simcenter_add_executable(NAME simCenterDprepro
                         FILES simCenterDprepro.cpp)
simcenter_add_python_script(SCRIPT preprocessJSON.py)
simcenter_add_python_script(SCRIPT DakotaFEM.py)
simcenter_add_python_script(SCRIPT DakotaFEM1.py)
