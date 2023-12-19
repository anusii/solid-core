| Function | Clinic | Indi | Podnotes | Suggested Package | Decided Package |
| -------- | ------ | ---- | -------- |------|------ |
|  getPermission  |   [getPermission](https://github.com/anusii/gurriny/blob/main/clinic/lib/models/common/rest_api.dart#L2265)     | [getPermission](https://github.com/anusii/gurriny/blob/main/indi/lib/models/common/rest_api.dart#L1627)      |    [getPermission](https://github.com/anusii/podnotes/blob/main/lib/common/rest_api/res_permission.dart#L47)      | | |
| addPermission | None | [addPermission](https://github.com/anusii/gurriny/blob/main/indi/lib/screens/settings/functions/add_permission.dart#L40) | [addPermission](https://github.com/anusii/podnotes/blob/main/lib/common/rest_api/res_permission.dart#L47) | | |
| setPermission | [setPermission](https://github.com/anusii/gurriny/blob/main/clinic/lib/models/common/rest_api.dart) | [setPermission](https://github.com/anusii/gurriny/blob/main/indi/lib/models/common/rest_api.dart#L1783) | [setPermission](https://github.com/anusii/podnotes/blob/main/lib/common/rest_api/res_permission.dart#L47) | | |
| copySharedKey | pods/clinic/lib/models/common/rest_api.dart | pods/indi/lib/models/common/rest_api.dart | podnotes/lib/common/rest_api/res_permission.dart | | |
| addPermLogLine | pods/clinic/lib/models/common/rest_api.dart | pods/indi/lib/models/common/rest_api.dart | podnotes/lib/common/rest_api/res_permission.dart | | |
| deletePermission | pods/clinic/lib/models/common/rest_api.dart | pods/indi/lib/models/common/rest_api.dart | podnotes/lib/common/rest_api/res_permission.dart | | |
| initialStructureTest | None | pods/indi/lib/models/common/rest_api.dart | podnotes/lib/common/rest_api/rest_api.dart| | |
|checkResourceExists| pods/clinic/lib/models/common/rest_api.dart |/pods/indi/lib/models/common/rest_api.dart | /podnotes/lib/common/rest_api/rest_api.dart | | |
| createItem | pods/clinic/lib/models/common/rest_api.dart | pods/indi/lib/models/common/rest_api.dart | podnotes/lib/common/rest_api/rest_api.dart | | |
|initialProfileUpdate| None | pods/indi/lib/models/common/rest_api.dart | podnotes/lib/common/rest_api/rest_api.dart | | |
| deleteItem | pods/clinic/lib/models/common/rest_api.dart | pods/indi/lib/models/common/rest_api.dart | podnotes/lib/common/rest_api/rest_api.dart | | |
| dividePubKeyStr| None |/pods/indi/lib/models/common/common_functions.dart|/podnotes/lib/constants/crypto.dart| | |
| genPubKeyStr | /pods/clinic/lib/models/common/common_functions.dart | /pods/indi/lib/models/common/common_functions.dart| /podnotes/lib/constants/crypto.dart | | |
|verifyEncKey|/pods/clinic/lib/models/common/encrypt_api.dart|/pods/indi/lib/models/common/encrypt_api.dart|/podnotes/lib/constants/crypto.dart| | |
| getFileContent | /pods/clinic/lib/models/common/common_functions.dart | /pods/indi/lib/models/common/common_functions.dart | /podnotes/lib/constants/rdf_functions.dart | | |
| getEncFileContent | /pods/clinic/lib/models/common/common_functions.dart | /pods/indi/lib/models/common/common_functions.dart | /podnotes/lib/constants/rdf_functions.dart | | |
| Class PodProfile | /pods/clinic/lib/models/rdf/get_rdf_data.dart | /pods/indi/lib/models/rdf/get_rdf_data.dart | /podnotes/lib/constants/rdf_functions.dart | | |
| Class AclResource | /pods/clinic/lib/models/rdf/get_rdf_data.dart | /pods/indi/lib/models/rdf/get_rdf_data.dart | /podnotes/lib/constants/rdf_functions.dart | | |
| genEncKeyBody | None | /pods/indi/lib/models/main/ontology.dart |/podnotes/lib/constants/turtle_structures.dart| | |
| genPubFileAclBody | None | /pods/indi/lib/models/main/ontology.dart|/podnotes/lib/constants/turtle_structures.dart| | |
| genPrvFileAclBody | None | /pods/indi/lib/models/main/ontology.dart|/podnotes/lib/constants/turtle_structures.dart| | |
|genPubDirAclBody|None|/pods/indi/lib/models/main/ontology.dart|/podnotes/lib/constants/turtle_structures.dart| | |
|genIndKeyFileBody|None|/pods/indi/lib/models/main/ontology.dart|/podnotes/lib/constants/turtle_structures.dart| | |
|genPubKeyFileBody|None|/pods/indi/lib/models/main/ontology.dart|/podnotes/lib/constants/turtle_structures.dart| | |
|genProfFileBody|None|/pods/indi/lib/models/main/ontology.dart|/podnotes/lib/constants/turtle_structures.dart| | |
|genLogFileBody|None|/pods/indi/lib/models/main/ontology.dart|/podnotes/lib/constants/turtle_structures.dart| | |
|genLogAclBody|None|/pods/indi/lib/models/main/ontology.dart|/podnotes/lib/constants/turtle_structures.dart| | |
| File initial_setup_desktop.dart | None | indi/lib/screens/profile/initial_setup_desktop.dart | podnotes/lib/initial_setup/initial_setup_desktop.dart| | |
| File initial_setup_screen.dart | None | indi/lib/screens/profile/initial_setup_screen.dart | podnotes/lib/initial_setup/initial_setup_screen.dart| | |
| launchIssuerReg | /pods/clinic/lib/screens/main/login_screen.dart | /pods/indi/lib/screens/main/login_screen.dart | /podnotes/lib/login/pod_reg.dart | | |
| Class _EncryptionKeyInputState | None | /pods/indi/lib/screens/settings/subPages/enc_key_input.dart |/podnotes/lib/master_key_setup/enc_key_input.dart | | |
| DataCell | None |/pods/indi/lib/models/main/constants.dart|/podnotes/lib/widgets/data_cell.dart| | |
| loadingScreen | None | /pods/indi/lib/models/main/constants.dart|/podnotes/lib/widgets/loading_screen.dart| | |
|getContentColour| None | /pods/indi/lib/models/common/common_widgets.dart | /podnotes/lib/widgets/msg_box.dart| | |
|assetSVG | None | /pods/indi/lib/models/common/common_widgets.dart | /podnotes/lib/widgets/msg_box.dart| | |
| Class AssestsPath | None | /pods/indi/lib/models/common/common_widgets.dart | /podnotes/lib/widgets/msg_box.dart| | |
| Class Languages | None | /pods/indi/lib/models/common/common_widgets.dart | /podnotes/lib/widgets/msg_box.dart| | |
| getWidgetHeight| None | /pods/indi/lib/models/common/common_widgets.dart | /podnotes/lib/widgets/msg_box.dart| | |
|buildMsgBox| None | /pods/indi/lib/models/common/common_widgets.dart | /podnotes/lib/widgets/msg_box.dart| | |