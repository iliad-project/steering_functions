^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package steering_functions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.0.3 (2018-04-27)
------------------

1.0.2 (2018-04-27)
------------------
* added missing install targets
* Merge branch 'master' of https://github.com/hbanzhaf/steering_functions into iliad
* Optimized integration of path
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Disabled timing test
* Contributors: Holger Banzhaf, Marc Hanheide

1.0.1 (2018-03-22)
------------------
* changed maintainer for iliad branch
* Fixed formating in README
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Updated README
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Renamed HC into HC_RS
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Renamed CC_Reeds_Shepp_State_Space into CC00_Reeds_Shepp_State_Space
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Implementation of CC_Dubins_State_Space added that allows for arbitrary start and goal curvature
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Moved two comments to their corresponding position
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Removed redundant computation in TTcTT family
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Improved visualization of state spaces by adding start and goal state without curvature to node
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Marked Dubins families in CC-Dubins state spaces
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Renamed CC_Dubins_State_Space into CC00_Dubins_State_Space
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Implementation of CCpmpm_State_Space added
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Implementation of CCpm0_State_Space added
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Removed unnecessary intermediate circle in HC_CC_RS_Path
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Implementation of CC0pm_State_Space added
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Integrated driving direction in continuous curvature dubins state space into computation of path
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Moved hc_cc_rs_path_type into namespace
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Modularized continuous curvature dubins state space
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Implementation of hybrid curvature state space added that allows for arbitrary start and goal curvature
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Added helper functions to paths.cpp
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Fixed bug in start and end configuration of hybrid curvature state spaces
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Updated README.md
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Moved reverse_control() to paths.cpp
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Removed vectorization for Eigen in CMakeLists.txt
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Robustified path integration.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Memory allocation of vectors now corresponding to their actual length
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Improved evaluation of configuration_equal()
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Merge branch 'master' of https://github.com/hbanzhaf/steering_functions
* Fixed bug in G2 continuous state spaces preventing them from being symmetric.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Added filter parameters to timing test.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Runtime optimization of filter.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Added dependency on Eigen in CMakeLists.txt
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Optimized computations in EKF.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Switched from computation of 4D covariances to computation of 3D covariances.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Merged computation of motion Jacobians.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Added timing of function get_path_with_covariance() to test.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Merge branch 'master' of https://github.com/hbanzhaf/steering_functions
* Moved timing of steering functions to separate test.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Simplified computation of Jacobians.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Integrated EKF in all steering functions.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Merge branch 'master' of https://github.com/hbanzhaf/steering_functions
* Simplified computation of end_of_clothoid().
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Added Jacobians for driving on clothoid.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Fixed bug in integration of dubins path.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Merge branch 'master' of https://github.com/hbanzhaf/steering_functions
* Modified function end_of_straight_line().
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Added test script for comparing analytic and numeric Jacobians.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Merge branch 'master' of https://github.com/hbanzhaf/steering_functions
* Modified integration of ODE by removing dependence on kappa.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Integrated utilities functions into EKF.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Merge branch 'master' of https://github.com/hbanzhaf/steering_functions
* Integrated utilities functions into Reeds-Shepp and Dubins state space.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Moved utilities to separate folder.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Reduced computation effort of function end_of_clothoid().
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Initial implementation of EKF interacting with Reeds-Shepp system added.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Merge branch 'master' of https://github.com/hbanzhaf/steering_functions
* Modified integration of ODE.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Added capability to get parameters required by the filter from yaml file.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Merged costmap_2d::transformFootprint() into node.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Using costmap_2d::transformFootprint() to orient polygons.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Added capability to visualize covariances.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Replaced look-up table for Fresnel integrals by Chebyshev polynomials.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Removed unnecessary functions in utilities.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Reduced cppcheck warnings.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Reading in footprint using costmap_2d's function makeFootprintFromParams()
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Removed IDE specific folder.
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Corrected computation of TTcT path in hc0pm_reeds_shepp_state_space by replacing a HC Turn with a required RS Turn
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Additional case added to HC Turn (if not regular && delta < delta_min/2)
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Heading angle at the end of clothoid and circular arc in HC/CC Steer now mapped to [-pi,pi[
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Added plotting script that plots the states of a path
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Bugfix in converting an arbitrary angle to [pi,-pi[ in HC/CC-Steer
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Interfacing with OMPL section added to README
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Merge remote-tracking branch 'origin/feature/interpolate'
* Removed unneccessary end_of_clothoid() evaluation in computation of cc_turn_controls()
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Renamed function forward_euler() into integrate_ODE()
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Interpolate function added to Reeds_Shepp_State_Space and Dubins_State_Space
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Interpolate function added to HC/CC Steer in order to interface steering functions with OMPL
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Separated computation of tangent circles in CC and HC Steer (families TT, TcT, TST) from computation of path length and updated computation times
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Initial commit with changes and additions made by H. Banzhaf
  Signed-off-by: Holger Banzhaf <holger.banzhaf@de.bosch.com>
* Initial code (DubinsStateSpace & ReedsSheppStateSpace) extracted from OMPL
* Initial code (CC-Steer) provided by T. Fraichard
* Contributors: Holger Banzhaf, Marc Hanheide
