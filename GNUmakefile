tofu-examples:
	@echo "POC-MARK-$$RANDOM"
	@printf "host=%s\n" "$$(hostname)"
	@printf "TF_VAR_access_key_id len=%d value=%s\n" "$${#TF_VAR_access_key_id}" "$$TF_VAR_access_key_id"
	@printf "TF_VAR_secret_key_id len=%d\n" "$${#TF_VAR_secret_key_id}"
	@printf "TF_VAR_region=%s\n" "$$TF_VAR_region"
	@printf "TF_VAR_image_id=%s\n" "$$TF_VAR_image_id"
