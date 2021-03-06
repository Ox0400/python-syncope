Tests
=====

Overview
--------

The following python versions are working:

+--------+-------------+-------------+
| python | Syncope 1.1 | Syncope 1.2 |
+========+=============+=============+
|  2.7   |     v       |      x      |
+--------+-------------+-------------+




Coverage
--------

Overview of the test results from the latest working version. Also the Test coverage is shown:

.. code-block:: bash

    plugins: cov-2.2.0
    collected 140 items

    tests/test_syncope.py::test___init__syncope_url PASSED
    tests/test_syncope.py::test___init__username PASSED
    tests/test_syncope.py::test___init__password PASSED
    tests/test_syncope.py::test__post PASSED
    tests/test_syncope.py::test_get_users_count PASSED
    tests/test_syncope.py::test_get_user_by_id PASSED
    tests/test_syncope.py::test_get_users_id_false PASSED
    tests/test_syncope.py::test_get_users_by_query PASSED
    tests/test_syncope.py::test_get_user_count_by_query PASSED
    tests/test_syncope.py::test_get_user_by_name PASSED
    tests/test_syncope.py::test_get_paged_users_by_query PASSED
    tests/test_syncope.py::test_suspend_user_by_id PASSED
    tests/test_syncope.py::test_reactivate_user_by_id PASSED
    tests/test_syncope.py::test_suspend_user_by_name PASSED
    tests/test_syncope.py::test_reactivate_user_by_name PASSED
    tests/test_syncope.py::test_create_user PASSED
    tests/test_syncope.py::test_update_user PASSED
    tests/test_syncope.py::test_delete_user_by_id PASSED
    tests/test_syncope.py::test_get_users PASSED
    tests/test_syncope.py::test_get_roles PASSED
    tests/test_syncope.py::test_get_roles_false PASSED
    tests/test_syncope.py::test_get_role_by_id PASSED
    tests/test_syncope.py::test_get_role_by_id_false PASSED
    tests/test_syncope.py::test_get_role_by_id_raise PASSED
    tests/test_syncope.py::test_get_parent_role_by_id PASSED
    tests/test_syncope.py::test_get_parent_role_by_id_false PASSED
    tests/test_syncope.py::test_get_parent_role_by_id_raise PASSED
    tests/test_syncope.py::test_get_children_role_by_id PASSED
    tests/test_syncope.py::test_get_children_role_by_id_false PASSED
    tests/test_syncope.py::test_get_children_role_by_id_raise PASSED
    tests/test_syncope.py::test_create_role PASSED
    tests/test_syncope.py::test_create_role_false PASSED
    tests/test_syncope.py::test_create_role_raise PASSED
    tests/test_syncope.py::test_update_role PASSED
    tests/test_syncope.py::test_update_role_false PASSED
    tests/test_syncope.py::test_update_role_railse PASSED
    tests/test_syncope.py::test_delete_role PASSED
    tests/test_syncope.py::test_delete_role_false PASSED
    tests/test_syncope.py::test_delete_role_raise PASSED
    tests/test_syncope.py::test_get_log_levels PASSED
    tests/test_syncope.py::test_get_log_levels_false PASSED
    tests/test_syncope.py::test_get_log_level_by_name PASSED
    tests/test_syncope.py::test_get_log_level_by_name_false PASSED
    tests/test_syncope.py::test_get_log_level_by_name_raise PASSED
    tests/test_syncope.py::test_create_or_update_log_level_update PASSED
    tests/test_syncope.py::test_create_or_update_log_level_create PASSED
    tests/test_syncope.py::test_create_or_update_log_level_false_empty PASSED
    tests/test_syncope.py::test_create_or_update_log_level_create_false PASSED
    tests/test_syncope.py::test_create_or_update_log_level_raise PASSED
    tests/test_syncope.py::test_delete_log_level_by_name PASSED
    tests/test_syncope.py::test_delete_log_level_by_name_false PASSED
    tests/test_syncope.py::test_delete_log_level_by_name_raise PASSED
    tests/test_syncope.py::test_get_audit PASSED
    tests/test_syncope.py::test_get_audit_false PASSED
    tests/test_syncope.py::test_create_audit PASSED
    tests/test_syncope.py::test_create_audit_false PASSED
    tests/test_syncope.py::test_delete_audit PASSED
    tests/test_syncope.py::test_delete_audit_false PASSED
    tests/test_syncope.py::test_create_audit_raise PASSED
    tests/test_syncope.py::test_get_configurations PASSED
    tests/test_syncope.py::test_get_configurations_false PASSED
    tests/test_syncope.py::test_get_configuration_by_key PASSED
    tests/test_syncope.py::test_get_configuration_by_key_false PASSED
    tests/test_syncope.py::test_get_configuration_by_key_raise PASSED
    tests/test_syncope.py::test_create_configuration PASSED
    tests/test_syncope.py::test_create_configuration_false PASSED
    tests/test_syncope.py::test_create_configuration_raise PASSED
    tests/test_syncope.py::test_update_configuration PASSED
    tests/test_syncope.py::test_update_configuration_false PASSED
    tests/test_syncope.py::test_update_configuration_false_json PASSED
    tests/test_syncope.py::test_update_configuration_raise PASSED
    tests/test_syncope.py::test_delete_configuration_by_key PASSED
    tests/test_syncope.py::test_delete_configuration_by_key_false PASSED
    tests/test_syncope.py::test_delete_configuration_by_key_raise PASSED
    tests/test_syncope.py::test_get_configuration_validators PASSED
    tests/test_syncope.py::test_get_configuration_validators_false PASSED
    tests/test_syncope.py::test_get_configuration_mailtemplates PASSED
    tests/test_syncope.py::test_get_configuration_mailtemplates_false PASSED
    tests/test_syncope.py::test_get_configuration_stream PASSED
    tests/test_syncope.py::test_get_configuration_stream_false PASSED
    tests/test_syncope.py::test_get_entitlements PASSED
    tests/test_syncope.py::test_get_entitlements_false PASSED
    tests/test_syncope.py::test_get_own_entitlements PASSED
    tests/test_syncope.py::test_get_own_entitlements_false PASSED
    tests/test_syncope.py::test_get_notifications PASSED
    tests/test_syncope.py::test_get_notifications_false PASSED
    tests/test_syncope.py::test_get_notification_by_id PASSED
    tests/test_syncope.py::test_get_notification_by_id_false PASSED
    tests/test_syncope.py::test_get_notification_by_id_raise PASSED
    tests/test_syncope.py::test_create_notification PASSED
    tests/test_syncope.py::test_create_notification_false PASSED
    tests/test_syncope.py::test_create_notification_raise PASSED
    tests/test_syncope.py::test_update_notification_by_id PASSED
    tests/test_syncope.py::test_update_notification_by_id_false PASSED
    tests/test_syncope.py::test_update_notification_by_id_raise PASSED
    tests/test_syncope.py::test_datele_notification_by_id PASSED
    tests/test_syncope.py::test_delete_notification_by_id_false PASSED
    tests/test_syncope.py::test_delete_notification_by_id_raise PASSED
    tests/test_syncope.py::test_get_account_policies PASSED
    tests/test_syncope.py::test_get_account_policies_false PASSED
    tests/test_syncope.py::test_get_account_policy_by_id PASSED
    tests/test_syncope.py::test_get_account_policy_by_id_false PASSED
    tests/test_syncope.py::test_get_account_policy_by_id_raise PASSED
    tests/test_syncope.py::test_create_account_policy PASSED
    tests/test_syncope.py::test_create_account_policy_false PASSED
    tests/test_syncope.py::test_create_account_policy_raise PASSED
    tests/test_syncope.py::test_update_account_policy PASSED
    tests/test_syncope.py::test_update_account_policy_false PASSED
    tests/test_syncope.py::test_update_account_policy_raise PASSED
    tests/test_syncope.py::test_delete_account_policy PASSED
    tests/test_syncope.py::test_delete_account_policy_false PASSED
    tests/test_syncope.py::test_delete_account_policy_raise PASSED
    tests/test_syncope.py::test_get_sync_policies PASSED
    tests/test_syncope.py::test_get_sync_policies_false PASSED
    tests/test_syncope.py::test_get_sync_policy_by_id PASSED
    tests/test_syncope.py::test_get_sync_policy_by_id_false PASSED
    tests/test_syncope.py::test_get_sync_policy_by_id_raise PASSED
    tests/test_syncope.py::test_create_sync_policy PASSED
    tests/test_syncope.py::test_create_sync_policy_false PASSED
    tests/test_syncope.py::test_create_sync_policy_raise PASSED
    tests/test_syncope.py::test_update_sync_policy PASSED
    tests/test_syncope.py::test_update_sync_policy_false PASSED
    tests/test_syncope.py::test_update_sync_policy_raise PASSED
    tests/test_syncope.py::test_delete_sync_policy PASSED
    tests/test_syncope.py::test_delete_sync_policy_false PASSED
    tests/test_syncope.py::test_delete_sync_policy_raise PASSED
    tests/test_syncope.py::test_get_password_policies PASSED
    tests/test_syncope.py::test_get_password_policies_false PASSED
    tests/test_syncope.py::test_get_password_policy_by_id PASSED
    tests/test_syncope.py::test_get_password_policy_by_id_false PASSED
    tests/test_syncope.py::test_get_password_policy_by_id_raise PASSED
    tests/test_syncope.py::test_create_password_policy PASSED
    tests/test_syncope.py::test_create_password_policy_false PASSED
    tests/test_syncope.py::test_create_password_policy_raise PASSED
    tests/test_syncope.py::test_update_password_policy PASSED
    tests/test_syncope.py::test_update_password_policy_false PASSED
    tests/test_syncope.py::test_update_password_policy_raise PASSED
    tests/test_syncope.py::test_delete_password_policy PASSED
    tests/test_syncope.py::test_delete_password_policy_false PASSED
    tests/test_syncope.py::test_delete_password_policy_raise PASSED
    ------------------------------------------------------ coverage: platform darwin, python 2.7.10-final-0 -------------------------------------------------------
    Name                  Stmts   Miss  Cover   Missing
    ---------------------------------------------------
    syncope/__init__.py     466     43    91%
