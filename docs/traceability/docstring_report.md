# IBM Storage Protect Docstring & Comments Coverage Report

## Summary
- **Total Python Files**: 46
- **Files Missing Module/File-level Docstring**: 0
- **Missing Class Docstrings**: 133
- **Missing Method Docstrings**: 25
- **Missing Function/Method Docstrings (excluding private/internal methods)**: 0

## Details per File

| File Path | File-level Docstring | Missing Class Docstrings | Missing Method Docstrings | Missing Function Docstrings |
|---|---|---|---|---|
| __init__.py | OK | None | None | None |
| base\__init__.py | OK | None | None | None |
| base\client.py | OK | None | None | None |
| c_api_bridge\__init__.py | OK | None | None | None |
| c_api_bridge\c_api\__init__.py | OK | None | None | None |
| c_api_bridge\c_api\load.py | OK | None | None | None |
| c_api_bridge\c_api\platform_types.py | OK | None | None | None |
| c_api_bridge\c_api\prototypes.py | OK | None | None | None |
| c_api_bridge\c_api\release.py | OK | None | None | None |
| c_api_bridge\c_api\return_codes.py | OK | None | None | None |
| c_api_bridge\c_api\structs.py | OK | PartialObjData, dsmDate, dsmApiVersion, dsmApiVersionEx, dsmAppVersion, dsmObjName, delBack, delArch, delBackID, dsmDelInfo, ObjAttr, mcBindKey, dsmGetList, DataBlk, qryMCData, archDetailCG, backupDetailCG, qryRespMCDetailData, qryRespMCData, qryArchiveData, qryRespArchiveData, sndArchiveData, qryBackupData, reservedInfo_t, qryRespBackupData, qryABackupData, qryARespBackupData, qryBackupGroups, qryProxyNodeData, qryRespProxyNodeData, dsmDosFSAttrib, dsmUnixFSAttrib, dsmFSAttr, dsmFSUpd, qryFSData, qryRespFSData, regFSData, ApiSessInfo, optStruct, logInfo, qryRespAccessData, envSetUp, dsmInitExIn_t, dsmInitExOut_t, dsmLogExIn_t, dsmLogExOut_t, dsmRenameIn_t, dsmRenameOut_t, dsmEndSendObjExIn_t, dsmEndSendObjExOut_t, dsmGroupHandlerIn_t, dsmGroupHandlerOut_t, dsmEndTxnExIn_t, dsmEndTxnExOut_t, dsmEndGetDataExIn_t, dsmEndGetDataExOut_t, dsmObjList_t, dsmRetentionEventIn_t, dsmRetentionEventOut_t, requestBufferIn_t, requestBufferOut_t, releaseBufferIn_t, releaseBufferOut_t, getBufferDataIn_t, getBufferDataOut_t, sendBufferDataIn_t, sendBufferDataOut_t, dsmUpdateObjExIn_t, dsmUpdateObjExOut_t | None | None |
| c_api_bridge\wrappers\__init__.py | OK | None | None | None |
| c_api_bridge\wrappers\backup\__init__.py | OK | None | None | None |
| c_api_bridge\wrappers\backup\batch.py | OK | None | None | None |
| c_api_bridge\wrappers\backup\group.py | OK | None | None | None |
| c_api_bridge\wrappers\backup\single.py | OK | None | None | None |
| c_api_bridge\wrappers\filespace.py | OK | None | None | None |
| c_api_bridge\wrappers\helper.py | OK | None | None | None |
| c_api_bridge\wrappers\object.py | OK | None | None | None |
| c_api_bridge\wrappers\query.py | OK | None | None | None |
| c_api_bridge\wrappers\restore\__init__.py | OK | None | None | None |
| c_api_bridge\wrappers\restore\batch.py | OK | None | None | None |
| c_api_bridge\wrappers\restore\group.py | OK | None | None | None |
| c_api_bridge\wrappers\restore\single.py | OK | None | None | None |
| c_api_bridge\wrappers\session.py | OK | None | None | None |
| control.py | OK | None | None | None |
| data_client\__init__.py | OK | None | None | None |
| data_client\backup.py | OK | None | None | None |
| data_client\client.py | OK | None | None | None |
| data_client\restore.py | OK | None | None | None |
| data_models\__init__.py | OK | None | None | None |
| data_models\backup.py | OK | Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config | GroupBackupRequest.validate_group_tag, GroupBackupRequest.validate_leader, BeginGroupBackupRequest.validate_group_tag, ReopenGroupBackupRequest.validate_group_tag, GroupRemoveMembersRequest.validate_member_obj_ids, GroupAssignToMembersRequest.validate_member_obj_ids, GroupDeleteRequest.validate_group_tag | None |
| data_models\filespace.py | OK | Config, Config, Config | FilespaceRegisterRequest.validate_filespace, FilespaceUpdateRequest.validate_filespace, FilespaceDeleteRequest.validate_filespace | None |
| data_models\object.py | OK | Config, Config, Config, Config | ObjectDeleteRequest.validate_key, ObjectDeleteRequest.validate_filespace, ObjectRenameRequest.validate_key, ObjectRenameRequest.validate_new_key, ObjectRenameRequest.validate_filespace, ObjectUpdateRequest.validate_key, ObjectUpdateRequest.validate_filespace | None |
| data_models\query.py | OK | Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config, Config | GroupQueryRequest.validate_filespace, BackupQueryRequest.validate_filespace, BackupQueryRequest.validate_key, ListObjectsRequest.validate_filespace, QueryObjectRequest.validate_filespace, QueryObjectRequest.validate_key | None |
| data_models\restore.py | OK | Config, Config, Config, Config, Config, Config, Config | RestoreRequest.validate_key | None |
| data_models\session.py | OK | None | LoginCredentials.__repr__ | None |
| enums.py | OK | None | None | None |
| errors\__init__.py | OK | None | None | None |
| errors\error_codes.py | OK | None | None | None |
| errors\exceptions.py | OK | TSMConnectionError, TSMAuthenticationError, TSMResourceError, TSMObjectError, TSMTransactionError, TSMConfigurationError, TSMOperationError, TSMDataError, TSMSystemError | None | None |
| errors\mapper.py | OK | None | None | None |
| logger\__init__.py | OK | None | None | None |
| logger\config.py | OK | None | None | None |
| logger\context.py | OK | None | None | None |
| logger\filters.py | OK | None | None | None |
| logger\formatters.py | OK | None | None | None |
| logger\operations.py | OK | None | None | None |
| query.py | OK | None | None | None |
| session.py | OK | None | None | None |