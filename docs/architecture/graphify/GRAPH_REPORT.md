# Graph Report - Reach  (2026-10-21)

## Corpus Check
- 280 files · ~282,128 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 12 file(s) not represented in the graph (top: (none) 3, .css 2, .xml 2)

## Summary
- 4074 nodes · 6339 edges · 254 communities (217 shown, 37 thin omitted)
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 78 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- tofu.ts
- install.rs
- tofu_commands.rs
- tofu.svelte.ts
- VaultError
- AppState
- ref_lib
- vault.ts
- vault.svelte.ts
- export.rs
- ansible.svelte.ts
- VaultManager
- hcl.rs
- SecretCategory
- SessionList.svelte
- bundle
- vault/manager.rs
- Terminal.svelte
- AnsibleWorkspace.svelte
- TofuDataSourcePanel.svelte
- SshManager
- getActiveProject
- svelte
- TofuOutputEditor.svelte
- VaultPanel.svelte
- VaultSelector.svelte
- Vault System Implementation Plan
- shortcuts.svelte.ts
- client.rs
- FileExplorer.svelte
- QuickConnect.svelte
- SessionEditor.svelte
- general.md
- package.json
- TofuWorkspace.svelte
- SecretList.svelte
- TunnelManager
- CodeEditor.svelte
- plugin/manager.rs
- TofuVariableEditor.svelte
- keyfile.rs
- ansible_commands.rs
- session_commands.rs
- collector.rs
- pty/manager.rs
- dependencies
- updater.svelte.ts
- LanguageStep.svelte
- TofuResourceConfigModal.svelte
- ansible.ts
- port.rs
- BackupTab.svelte
- TofuProjectList.svelte
- TofuProviderPanel.svelte
- TofuStatePanel.svelte
- TunnelManager.svelte
- ai.svelte.ts
- ansible.md
- SyncTab.svelte
- TofuModulePanel.svelte
- TofuResourcePicker.svelte
- crypto.rs
- docs/package.json
- plugin_commands.rs
- SecretEditor.svelte
- ai-chat.svelte.ts
- TofuCommand
- Changelog
- AppShell.svelte
- SshConfigImport.svelte
- SnippetPanel.svelte
- TofuLocalsPanel.svelte
- InviteMemberDialog.svelte
- plugin.svelte.ts
- settings.svelte.ts
- exec_on_connection
- state.rs
- plugin.ts
- lib.rs
- @tauri-apps/api
- PluginPanel.svelte
- tofu/types.rs
- serialize
- TofuProjectManager
- marketplace_commands.rs
- EditorWindow.svelte
- SplitPane.svelte
- TofuEnvironmentPanel.svelte
- ssh.ts
- host_api.rs
- ssh_commands.rs
- AnsibleProjectManager
- TofuGraphPanel.svelte
- hooks.rs
- ai_commands.rs
- settings_commands.rs
- marketplace.rs
- transfer.rs
- Sidebar.svelte
- sessions.ts
- sessions.svelte.ts
- credential_commands.rs
- sandbox.rs
- ssh/config.rs
- GeneralTab.svelte
- AnsibleInventoryPanel.svelte
- ShareDialog.svelte
- AppearanceTab.svelte
- SecurityTab.svelte
- MonitoringBar.svelte
- TofuProviderPicker.svelte
- PluginPermission
- UiElement
- SshClientHandler
- sftp_commands.rs
- devDependencies
- compilerOptions
- TofuProjectEditor.svelte
- AIPanel.svelte
- AnsibleAdHocPanel.svelte
- AnsibleProjectEditor.svelte
- MarketplacePanel.svelte
- VirtualList.svelte
- snippets.svelte.ts
- AnsibleCommand
- templates.rs
- README.md
- file-explorer.md
- ssh-terminal.md
- AnsiblePlaybookPanel.svelte
- loadSessions
- AITab.svelte
- PluginsTab.svelte
- TofuBackendPanel.svelte
- TofuPlanViewer.svelte
- explorer.svelte.ts
- TofuProject
- opentofu.md
- plugins.md
- closeContextMenu
- KeyPathInput.svelte
- Dropdown.svelte
- marketplace.ts
- sftp.ts
- plugin/schema.rs
- jump-hosts.md
- sync/setup.md
- snippet_commands.rs
- AnsibleRolesPanel.svelte
- TitleBar.svelte
- TofuHclPreview.svelte
- toasts.svelte.ts
- transfers.svelte.ts
- plan_parser.rs
- TofuChangeAction
- sessions.md
- tunnels.md
- graph.rs
- TabBar.svelte
- UpdateDialog.svelte
- TofuWorkspacePanel.svelte
- +page.svelte
- installation.md
- tofu/schema.rs
- refresh
- i18n.svelte.ts
- passwords.svelte.ts
- terminal-buffer.svelte.ts
- formatters.ts
- serial_commands.rs
- tunnel_commands.rs
- TofuVarType
- ai-assistant.md
- first-run.md
- scripts
- i18n-check.js
- monitoring.svelte.ts
- runCommand
- monitoring_commands.rs
- sshconfig_commands.rs
- Actions
- serial.md
- shortcuts.md
- troubleshooting.md
- encryption.md
- extract-icons.mjs
- loadDirectory
- Settings.svelte
- Input.svelte
- index.ts
- snippets.ts
- sshconfig.ts
- tunnel.ts
- default.json
- ProviderFieldType
- Starlight Starter Kit: Basics
- development/setup.md
- Providers
- introduction.md
- shared-vaults.md
- what-is-turso.md
- backup.md
- sharing.md
- docs/tsconfig.json
- What's inside
- StatusBar.svelte
- Toggle.svelte
- distro-icons.ts
- toolchain.ts
- navigation.svelte.ts
- PluginStatus
- SessionCommand
- architecture.md
- monitoring.md
- Resources
- Backend
- Workspaces
- State
- uploadFile
- refreshFiles
- positionMenu.ts
- PluginAppState
- TofuExecutionTarget
- sessionCreate
- Modules
- Variables
- Projects
- Environments
- Workspace
- Outputs
- updates.md
- virtual-scroll.ts
- +layout.ts
- index.mdx
- ContextMenuBackdrop.svelte
- version.ts
- reach

## God Nodes (most connected - your core abstractions)
1. `AppState` - 210 edges
2. `VaultError` - 112 edges
3. `VaultManager` - 110 edges
4. `svelte` - 42 edges
5. `getActiveProject()` - 41 edges
6. `@tauri-apps/api` - 35 edges
7. `SshManager` - 28 edges
8. `SecretCategory` - 27 edges
9. `exec_on_connection()` - 26 edges
10. `SshError` - 25 edges

## Surprising Connections (you probably didn't know these)
- `v0.4.1` --references--> `sendResize()`  [INFERRED]
  CHANGELOG.md → src/lib/components/terminal/Terminal.svelte
- `v0.4.1` --references--> `safeFitAndResize()`  [INFERRED]
  CHANGELOG.md → src/lib/components/terminal/Terminal.svelte
- `v0.4.2` --references--> `PluginConfig`  [INFERRED]
  CHANGELOG.md → src/lib/ipc/plugin.ts
- `v0.3.7` --references--> `sessionCreate()`  [INFERRED]
  CHANGELOG.md → src/lib/ipc/sessions.ts
- `v0.3.8` --references--> `sessionCreate()`  [INFERRED]
  CHANGELOG.md → src/lib/ipc/sessions.ts

## Import Cycles
- 2-file cycle: `src-tauri/src/state.rs -> src-tauri/src/tunnel/manager.rs -> src-tauri/src/state.rs`
- 2-file cycle: `src-tauri/src/monitoring/collector.rs -> src-tauri/src/state.rs -> src-tauri/src/monitoring/collector.rs`
- 3-file cycle: `src-tauri/src/plugin/manager.rs -> src-tauri/src/tunnel/manager.rs -> src-tauri/src/state.rs -> src-tauri/src/plugin/manager.rs`
- 4-file cycle: `src-tauri/src/plugin/host_api.rs -> src-tauri/src/tunnel/manager.rs -> src-tauri/src/state.rs -> src-tauri/src/plugin/manager.rs -> src-tauri/src/plugin/host_api.rs`

## Communities (254 total, 37 thin omitted)

### Community 0 - "tofu.ts"
Cohesion: 0.03
Nodes (39): BackendCatalogEntry, DataSourceCatalogEntry, DependencyGraph, FieldOption, GeneratedFile, GraphEdge, GraphNode, HclGenerationResult (+31 more)

### Community 1 - "install.rs"
Cohesion: 0.06
Nodes (40): build_command_args(), run_local(), run_remote(), shell_escape(), should_use_wsl(), silent_async_command(), silent_command(), editor_get_pending_file() (+32 more)

### Community 2 - "tofu_commands.rs"
Cohesion: 0.07
Nodes (40): run_tofu_sync(), run_tofu_sync_full(), silent_async_command(), tofu_apply_template(), tofu_create_project(), tofu_delete_project(), tofu_fetch_schema(), tofu_fmt() (+32 more)

### Community 3 - "tofu.svelte.ts"
Cohesion: 0.03
Nodes (28): activeProjectId, backendCatalog, commandOutput, commandRunning, currentRunId, dataSourceCatalog, dependencyGraph, dynamicSchema (+20 more)

### Community 4 - "VaultError"
Cohesion: 0.06
Nodes (40): VaultError, AccessDenied, AlreadyExists, CryptoError, DatabaseError, DecryptionError, EncryptionError, IdentityAlreadyExists (+32 more)

### Community 5 - "AppState"
Cohesion: 0.09
Nodes (45): turso_create_database(), turso_create_database_token(), vault_accept_invite(), vault_accept_shared_item(), vault_auto_unlock(), vault_close(), vault_create(), vault_delete() (+37 more)

### Community 6 - "ref_lib"
Cohesion: 0.04
Nodes (37): { entry, onclick, oncontextmenu, ondownload }, Props, sizeText, hasCompleted, transfers, { element, onAction }, Props, Props (+29 more)

### Community 7 - "vault.ts"
Cohesion: 0.04
Nodes (10): AppSettings, BackupPreview, InviteInfo, MemberInfo, ReceivedShare, SecretMetadata, SharedItemInfo, ShareItemResult (+2 more)

### Community 8 - "vault.svelte.ts"
Cohesion: 0.06
Nodes (39): acceptInvite(), acceptSharedItem(), autoUnlock(), checkState(), closeVault(), createSecret(), createVault(), deleteSecret() (+31 more)

### Community 9 - "export.rs"
Cohesion: 0.07
Nodes (31): PublicKey, BackupPreview, derive_export_key(), ExportBundle, ExportedIdentity, ExportedMember, ExportedSecret, ExportedSyncConfig (+23 more)

### Community 10 - "ansible.svelte.ts"
Cohesion: 0.05
Nodes (23): activeProjectId, collections, collectionsLoading, commandOutput, commandRunning, currentRunId, generateInventory(), getActiveProject() (+15 more)

### Community 11 - "VaultManager"
Cohesion: 0.07
Nodes (8): ensure_plugin_vault(), get_plugin_vault_id_if_exists(), load_plugin_config(), load_plugin_configs(), PLUGIN_VAULT_NAME, save_plugin_config(), now_timestamp(), VaultManager

### Community 12 - "hcl.rs"
Cohesion: 0.10
Nodes (19): get_backend_catalog(), get_provider_catalog(), get_data_source_catalog(), collect_nested_fields(), format_default_value(), generate_all(), generate_backend_block(), generate_data_sources_tf() (+11 more)

### Community 13 - "SecretCategory"
Cohesion: 0.05
Nodes (27): AppSettings, InviteInfo, MemberInfo, MemberRole, Admin, Member, Owner, ReadOnly (+19 more)

### Community 14 - "SessionList.svelte"
Cohesion: 0.04
Nodes (38): collapsedFolders, connectError, connecting, connectingId, connectKeyPassphrase, connectPassword, connectSession, contextMenu (+30 more)

### Community 15 - "bundle"
Cohesion: 0.04
Nodes (45): app, security, windows, withGlobalTauri, build, beforeBuildCommand, beforeDevCommand, devUrl (+37 more)

### Community 16 - "vault/manager.rs"
Cohesion: 0.06
Nodes (14): CREDENTIALS_VAULT, FOLDERS_VAULT, get_key_from_keychain(), PLAYBOOKS_VAULT, SESSIONS_VAULT, SETTINGS_VAULT, SNIPPETS_VAULT, StoredIdentity (+6 more)

### Community 17 - "Terminal.svelte"
Cohesion: 0.08
Nodes (29): v0.4.1, acceptSuggestion(), appSettings, clearGhostDecoration(), containerEl, copySelection(), currentConnectionId, disconnected (+21 more)

### Community 18 - "AnsibleWorkspace.svelte"
Cohesion: 0.05
Nodes (27): collectionsList, installName, loading, project, Props, running, { target }, output (+19 more)

### Community 19 - "TofuDataSourcePanel.svelte"
Cohesion: 0.06
Nodes (29): activeProviderIds, activeProviders, categories, Category, closeConfig(), closePicker(), configCatalogEntry, configDataSource (+21 more)

### Community 20 - "SshManager"
Cohesion: 0.14
Nodes (14): ActiveConnection, ConnectionInfo, exec_on_connection_streaming(), exec_on_connection_with_exit_code(), into_active_connection(), open_interactive_shell(), ssh_session_task(), SshError (+6 more)

### Community 21 - "getActiveProject"
Cohesion: 0.08
Nodes (36): addProvider(), addResource(), applyTemplate(), createWorkspace(), deleteWorkspace(), fetchSchema(), generateHcl(), getActiveBackend() (+28 more)

### Community 22 - "svelte"
Cohesion: 0.07
Nodes (16): svelte, deletingId, projectList, showEditor, installDone, installing, installLogs, installSuccess (+8 more)

### Community 23 - "TofuOutputEditor.svelte"
Cohesion: 0.06
Nodes (25): canSave, description, handleKeydown(), handleSave(), isEditing, name, nameDuplicate, nameError (+17 more)

### Community 24 - "VaultPanel.svelte"
Cohesion: 0.06
Nodes (27): activeVault, activeVaultId, confirmPassword, creatingVault, error, handleBackToList(), handleCreateIdentity(), handleKeydown() (+19 more)

### Community 25 - "VaultSelector.svelte"
Cohesion: 0.07
Nodes (25): creating, deleting, error, handleInvite(), inviteePublicKey, inviteeRole, inviteeUuid, inviteResult (+17 more)

### Community 26 - "Vault System Implementation Plan"
Cohesion: 0.06
Nodes (32): 1. User-Visible Vaults, 2. Session-to-Vault Assignment, 3. Vault Membership (for shared), 4. Turso Sync Integration, Backend Changes Needed, Backend (Rust), Core Concepts, Create Vault Dialog (+24 more)

### Community 27 - "shortcuts.svelte.ts"
Cohesion: 0.09
Nodes (22): toggleAIPanel(), cleanupShortcuts(), closeActiveTab(), initShortcuts(), isMac(), matchesShortcut(), nextTab(), normalizeKey() (+14 more)

### Community 28 - "client.rs"
Cohesion: 0.08
Nodes (17): AuthParams, hostkey_prompts(), HOSTKEY_PROMPTS, HostKeyPrompt, init_for_fish_avoids_bash_syntax(), JumpHostParams, KeyAuth, KnownHosts (+9 more)

### Community 29 - "FileExplorer.svelte"
Cohesion: 0.06
Nodes (22): activeTransfers, { connectionId }, contextMenu, creatingFile, creatingFolder, currentPath, deleteConfirm, dragging (+14 more)

### Community 30 - "QuickConnect.svelte"
Cohesion: 0.06
Nodes (28): authMethod, canConnect, connecting, error, host, jumpAuthMethod, jumpEnabled, jumpHost (+20 more)

### Community 31 - "SessionEditor.svelte"
Cohesion: 0.06
Nodes (25): authType, canSave, error, folderIdStr, host, isEditing, jumpEnabled, jumpHops (+17 more)

### Community 32 - "general.md"
Cohesion: 0.07
Nodes (29): Accept Invite, AI, API Key, Appearance, Backup, Cloud Sync Setup, Default Shell, Discovery and Reload (+21 more)

### Community 33 - "package.json"
Cohesion: 0.07
Nodes (25): name, private, type, version, codemirror, @codemirror/lang-yaml, @codemirror/state, svelte-check (+17 more)

### Community 34 - "TofuWorkspace.svelte"
Cohesion: 0.07
Nodes (24): output, running, scrollContainer, activeEnvName, activeTab, autoApprove, buildTarget(), connections (+16 more)

### Community 35 - "SecretList.svelte"
Cohesion: 0.07
Nodes (17): categories, creating, deleting, editValue, loadingSecret, newCategory, newName, newValue (+9 more)

### Community 36 - "TunnelManager"
Cohesion: 0.12
Nodes (10): ActiveTunnel, relay_connection(), TunnelError, ConnectionNotFound, CreationFailed, IoError, NotFound, NotImplemented (+2 more)

### Community 37 - "CodeEditor.svelte"
Cohesion: 0.08
Nodes (17): @codemirror/autocomplete, @codemirror/commands, codemirror-lang-hcl, @codemirror/language, @codemirror/language-data, @codemirror/lint, @codemirror/search, @codemirror/theme-one-dark (+9 more)

### Community 38 - "plugin/manager.rs"
Cohesion: 0.14
Nodes (4): get_ui_from_lua(), make_plugin_info(), PluginInstance, PluginManager

### Community 39 - "TofuVariableEditor.svelte"
Cohesion: 0.08
Nodes (20): canSave, defaultValue, description, handleKeydown(), handleSave(), isEditing, name, nameDuplicate (+12 more)

### Community 40 - "keyfile.rs"
Cohesion: 0.16
Nodes (26): expand_tilde(), bare_type_without_base64_is_not_public_key(), classify_path(), detect_encrypted(), detects_ecdsa_public_key(), detects_ed25519_public_key_with_comment(), detects_encrypted_classic_pem(), detects_openssh_private_key() (+18 more)

### Community 41 - "ansible_commands.rs"
Cohesion: 0.15
Nodes (15): ansible_create_project(), ansible_delete_project(), ansible_generate_inventory(), ansible_list_collections(), ansible_list_files(), ansible_list_projects(), ansible_list_roles(), ansible_open_project() (+7 more)

### Community 42 - "session_commands.rs"
Cohesion: 0.17
Nodes (17): ensure_folders_vault(), ensure_sessions_vault(), find_session_vault(), FOLDERS_VAULT_NAME, get_folders_vault_id_if_exists(), get_sessions_vault_id(), get_sessions_vault_id_if_exists(), session_create() (+9 more)

### Community 43 - "collector.rs"
Cohesion: 0.13
Nodes (16): CollectorError, CommandFailed, NotConnected, ParseError, CPU_COMMAND, CpuSnapshot, monitoring_loop(), MonitoringCollector (+8 more)

### Community 44 - "pty/manager.rs"
Cohesion: 0.14
Nodes (11): detect_default_shell(), pty_reader_loop(), PtyError, NotFound, ReadError, ResizeFailed, SpawnFailed, WriteError (+3 more)

### Community 45 - "dependencies"
Cohesion: 0.08
Nodes (25): dependencies, codemirror, @codemirror/autocomplete, @codemirror/commands, codemirror-lang-hcl, @codemirror/lang-yaml, @codemirror/language, @codemirror/language-data (+17 more)

### Community 46 - "updater.svelte.ts"
Cohesion: 0.10
Nodes (20): @tauri-apps/plugin-process, @tauri-apps/plugin-updater, checkForUpdate(), dismissed, downloadAndInstall(), downloadAttempts, downloading, downloadProgress (+12 more)

### Community 47 - "LanguageStep.svelte"
Cohesion: 0.08
Nodes (16): hasTurso, { onComplete, onBack }, Props, settings, storageLabel, languages, { onNext }, Props (+8 more)

### Community 48 - "TofuResourceConfigModal.svelte"
Cohesion: 0.09
Nodes (16): catalogEntry, fields, handleSave(), logicalName, nameError, Props, resourceConfig, { resourceId, onclose } (+8 more)

### Community 49 - "ansible.ts"
Cohesion: 0.08
Nodes (9): AnsibleCollection, AnsibleCommand, AnsibleCommandEvent, AnsibleCommandRequest, AnsibleExecutionTarget, AnsibleInventoryGroup, AnsibleInventoryHost, AnsibleProject (+1 more)

### Community 50 - "port.rs"
Cohesion: 0.14
Nodes (9): ActiveSerialPort, list_ports(), SerialError, AlreadyOpen, EnumerationFailed, IoError, NotOpen, PortNotFound (+1 more)

### Community 51 - "BackupTab.svelte"
Cohesion: 0.09
Nodes (17): canExport, canImport, canVerify, exportConfirmPassword, exportError, exporting, exportPassword, handleImport() (+9 more)

### Community 52 - "TofuProjectList.svelte"
Cohesion: 0.09
Nodes (12): deletingId, pendingTemplateId, projectList, showEditor, showTemplatePicker, activeCategory, categories, filteredTemplates (+4 more)

### Community 53 - "TofuProviderPanel.svelte"
Cohesion: 0.09
Nodes (15): catalogEntry, fields, Props, providerConfig, { providerId, onclose }, version, catalog, configProviderId (+7 more)

### Community 54 - "TofuStatePanel.svelte"
Cohesion: 0.09
Nodes (12): address, { open, onclose, onimport }, Props, resourceId, loading, moveDestination, movingAddress, Props (+4 more)

### Community 55 - "TunnelManager.svelte"
Cohesion: 0.09
Nodes (14): Props, { tunnel, onstart, onstop }, typeColor, typeLabel, { connectionId }, creating, formLocalPort, formRemoteHost (+6 more)

### Community 56 - "ai.svelte.ts"
Cohesion: 0.11
Nodes (15): AISettings, loadSecureAISettings(), models, modelsError, modelsLoading, OpenRouterModel, saveAISettings(), saveLocalSettings() (+7 more)

### Community 57 - "ansible.md"
Cohesion: 0.09
Nodes (21): Ad-Hoc, Collections, Command output, Creating a project, Data storage, Execution target, Groups, Hosts (+13 more)

### Community 58 - "SyncTab.svelte"
Cohesion: 0.09
Nodes (16): acceptingInvite, error, exportedKey, inviteSyncUrl, inviteToken, loading, personalDbToken, personalDbUrl (+8 more)

### Community 59 - "TofuModulePanel.svelte"
Cohesion: 0.11
Nodes (15): editing, formInputs, formName, formSource, formVersion, handleAdd(), handleBackdropClick(), handleClose() (+7 more)

### Community 60 - "TofuResourcePicker.svelte"
Cohesion: 0.10
Nodes (17): activeProviderIds, activeProviders, catalog, categories, Category, existingResources, filteredCatalog, handleAdd() (+9 more)

### Community 61 - "crypto.rs"
Cohesion: 0.24
Nodes (17): decrypt_secret(), encrypt_secret(), generate_dek(), generate_nonce(), test_encrypt_decrypt_secret(), test_wrap_unwrap_dek(), unwrap_dek(), unwrap_dek_with_dek() (+9 more)

### Community 62 - "docs/package.json"
Cohesion: 0.10
Nodes (17): dependencies, astro, @astrojs/starlight, sharp, name, scripts, astro, build (+9 more)

### Community 63 - "plugin_commands.rs"
Cohesion: 0.19
Nodes (12): plugin_call_action(), plugin_discover(), plugin_dispatch_hook(), plugin_get_config(), plugin_get_dir(), plugin_get_ui(), plugin_list(), plugin_load() (+4 more)

### Community 64 - "SecretEditor.svelte"
Cohesion: 0.10
Nodes (14): canSave, categories, category, isEditMode, isMonospace, loading, modalTitle, name (+6 more)

### Community 65 - "ai-chat.svelte.ts"
Cohesion: 0.16
Nodes (16): AIChatMessage, aiInvoke(), buildSystemPrompt(), captureCommandOutput(), decodePayload(), error, executeCommand(), extractCodeBlocks() (+8 more)

### Community 66 - "TofuCommand"
Cohesion: 0.10
Nodes (20): TofuCommand, Apply, Destroy, Fmt, FmtCheck, Import, Init, Output (+12 more)

### Community 67 - "Changelog"
Cohesion: 0.10
Nodes (20): Changelog, v0.1.6, v0.1.7, v0.1.8, v0.1.9, v0.2.0, v0.2.1, v0.2.2 (+12 more)

### Community 68 - "AppShell.svelte"
Cohesion: 0.12
Nodes (16): activeConnectionId, activeTab, { children }, closeCount, closeMode, closeOpen, confirmClose(), countActiveConnections() (+8 more)

### Community 69 - "SshConfigImport.svelte"
Cohesion: 0.11
Nodes (12): canImport, error, existingSessions, hosts, importing, isAlreadyImported(), loading, { open = $bindable(), onsave } (+4 more)

### Community 70 - "SnippetPanel.svelte"
Cohesion: 0.11
Nodes (14): activeTab, { connectionId }, editingId, executeSnippet(), filtered, newCommand, newDescription, newName (+6 more)

### Community 71 - "TofuLocalsPanel.svelte"
Cohesion: 0.11
Nodes (16): canSave, editing, existingNames, expression, handleAdd(), handleKeydown(), handleSave(), locals (+8 more)

### Community 72 - "InviteMemberDialog.svelte"
Cohesion: 0.11
Nodes (16): activeTab, error, handleInvite(), handleRemoveMember(), inviteePublicKey, inviteeRole, inviteeUuid, inviteResult (+8 more)

### Community 73 - "plugin.svelte.ts"
Cohesion: 0.10
Nodes (6): activePluginId, discoveredManifests, error, loading, plugins, pluginUiStates

### Community 74 - "settings.svelte.ts"
Cohesion: 0.12
Nodes (10): defaults, restoreLocalSettingsFromVault(), saveSettings(), secureDefaults, secureError, secureLoading, SecureSettings, Settings (+2 more)

### Community 75 - "exec_on_connection"
Cohesion: 0.25
Nodes (17): delete_entry(), list_directory(), make_directory(), MAX_EDIT_SIZE, parse_ls_output(), read_text_file(), RemoteEntry, rename_entry() (+9 more)

### Community 76 - "state.rs"
Cohesion: 0.13
Nodes (15): AuthMethod, Agent, Key, Password, Folder, JumpHostConfig, ProxyConfig, SessionConfig (+7 more)

### Community 77 - "plugin.ts"
Cohesion: 0.11
Nodes (6): v0.4.2, PluginConfig, PluginManifest, PluginStatus, PluginUiState, UiElement

### Community 78 - "lib.rs"
Cohesion: 0.15
Nodes (11): pty_close(), pty_resize(), pty_spawn(), pty_write(), APP_DATA_DIR, app_data_dir(), get_close_to_tray(), quit_app() (+3 more)

### Community 79 - "@tauri-apps/api"
Cohesion: 0.11
Nodes (6): @tauri-apps/api, handleReset(), SystemStats, AppSettings, SETTING_KEYS, EditorFile

### Community 80 - "PluginPanel.svelte"
Cohesion: 0.12
Nodes (15): isEnabled, { plugin, active, onclick, onToggle }, Props, statusLabel, activePluginId, activeTab, { connectionId }, discovering (+7 more)

### Community 81 - "tofu/types.rs"
Cohesion: 0.18
Nodes (18): BackendCatalogEntry, DataSourceCatalogEntry, DependencyGraph, FieldOption, GeneratedFile, GraphEdge, GraphNode, HclGenerationResult (+10 more)

### Community 82 - "serialize"
Cohesion: 0.14
Nodes (13): AnsibleCollection, AnsibleCommandEvent, AnsibleCommandRequest, AnsibleExecutionTarget, Local, Ssh, AnsibleInventoryGroup, AnsibleInventoryHost (+5 more)

### Community 83 - "TofuProjectManager"
Cohesion: 0.19
Nodes (4): ensure_tofu_vault(), now_iso8601(), TofuProjectManager, TOFU_PROJECTS_VAULT

### Community 84 - "marketplace_commands.rs"
Cohesion: 0.19
Nodes (13): marketplace_fetch(), marketplace_get_url(), marketplace_install(), marketplace_load_url(), marketplace_reset_url(), marketplace_set_url(), marketplace_uninstall(), MARKETPLACE_URL_KEY (+5 more)

### Community 85 - "EditorWindow.svelte"
Cohesion: 0.12
Nodes (11): activeTab, activeTabId, addOrActivateTab(), availableLanguages, detectLanguage(), dirty, EditorTab, makeTabId() (+3 more)

### Community 86 - "SplitPane.svelte"
Cohesion: 0.11
Nodes (14): containerEl, containerHeight, containerSize, containerWidth, {
		direction,
		initialRatio = 0.5,
		minSize = 100,
		first,
		second
	}, dividerStyle, firstSize, firstStyle (+6 more)

### Community 87 - "TofuEnvironmentPanel.svelte"
Cohesion: 0.13
Nodes (14): activeEnvName, catalog, environments, handleAddEnvironment(), handleDeleteEnvironment(), localValues, newEnvName, providers (+6 more)

### Community 88 - "ssh.ts"
Cohesion: 0.11
Nodes (8): ConnectionInfo, HostKeyPrompt, JumpHostConnectParams, KeyCandidate, KeyFileInfo, KeyFileKind, ProxyConfig, SshConnectParams

### Community 89 - "host_api.rs"
Cohesion: 0.35
Nodes (11): http_client(), inject_host_api(), inject_http_api(), inject_log_api(), inject_notify_api(), inject_sftp_api(), inject_ssh_api(), inject_tunnel_api() (+3 more)

### Community 90 - "ssh_commands.rs"
Cohesion: 0.19
Nodes (10): build_auth(), inspect_key_file(), JumpHostConnectParams, ssh_connect(), ssh_detect_os(), ssh_disconnect(), ssh_list_connections(), ssh_ready() (+2 more)

### Community 91 - "AnsibleProjectManager"
Cohesion: 0.21
Nodes (4): AnsibleProjectManager, ensure_ansible_vault(), now_iso8601(), ANSIBLE_PROJECTS_VAULT

### Community 92 - "TofuGraphPanel.svelte"
Cohesion: 0.12
Nodes (9): graph, isPanning, loading, panStartX, panStartY, providerColors, viewBoxScale, viewBoxX (+1 more)

### Community 93 - "hooks.rs"
Cohesion: 0.16
Nodes (15): HOOK_SESSION_CONNECTED, HOOK_SESSION_DISCONNECTED, HOOK_SFTP_DOWNLOAD_COMPLETE, HOOK_SFTP_UPLOAD_COMPLETE, HOOK_TUNNEL_STARTED, HOOK_TUNNEL_STOPPED, HOOK_VAULT_LOCKED, HOOK_VAULT_UNLOCKED (+7 more)

### Community 94 - "ai_commands.rs"
Cohesion: 0.22
Nodes (15): ai_chat(), ai_fetch_models(), AiChatRequest, AiFetchModelsRequest, AiMessage, ApiError, Choice, ChoiceMessage (+7 more)

### Community 95 - "settings_commands.rs"
Cohesion: 0.25
Nodes (14): AppSettings, DEFAULT_AI_MODEL, ensure_settings_vault(), get_settings_vault_id_if_exists(), OPENROUTER_API_KEY, OPENROUTER_URL, read_setting(), save_setting() (+6 more)

### Community 96 - "marketplace.rs"
Cohesion: 0.21
Nodes (8): char_for_nibble(), download_client(), extract_zip_safely(), fetch_index(), hex_lower(), install_entry(), MarketplaceEntry, MAX_DOWNLOAD_BYTES

### Community 97 - "transfer.rs"
Cohesion: 0.21
Nodes (9): download_file(), TransferError, Cancelled, FileNotFound, IoError, NotConnected, SshError, TransferProgress (+1 more)

### Community 98 - "Sidebar.svelte"
Cohesion: 0.15
Nodes (11): activeSection, { collapsed = $bindable(false), connectionId }, dragging, Props, saveWidth(), Section, sections, sidebarWidth (+3 more)

### Community 99 - "sessions.ts"
Cohesion: 0.13
Nodes (6): AuthMethod, Folder, JumpHostConfig, ProxySessionConfig, SessionConfig, ShareResult

### Community 100 - "sessions.svelte.ts"
Cohesion: 0.13
Nodes (6): deleteFolder(), Folder, folders, Session, sessionList, sessions

### Community 101 - "credential_commands.rs"
Cohesion: 0.28
Nodes (13): credential_delete_password(), credential_get_password(), credential_has_master_password(), credential_has_password(), credential_is_locked(), credential_lock(), credential_save_password(), credential_set_master_password() (+5 more)

### Community 102 - "sandbox.rs"
Cohesion: 0.19
Nodes (3): create_sandbox(), ExecutionLimits, LUA_INTERRUPT_LIMIT

### Community 103 - "ssh/config.rs"
Cohesion: 0.36
Nodes (10): JumpHostEntry, list_hosts(), parse_ssh_config(), resolve_host(), resolve_jump_recursive(), resolve_proxy_jump(), resolve_tilde(), ssh_config_path() (+2 more)

### Community 104 - "GeneralTab.svelte"
Cohesion: 0.14
Nodes (5): @tauri-apps/plugin-autostart, @tauri-apps/plugin-shell, languageOptions, settings, shellOptions

### Community 105 - "AnsibleInventoryPanel.svelte"
Cohesion: 0.14
Nodes (6): editingGroup, editingHost, groups, hosts, iniPreview, project

### Community 106 - "ShareDialog.svelte"
Cohesion: 0.14
Nodes (11): error, expiresInHours, myPublicKey, myUuid, Props, recipientPublicKey, recipientUuid, { session, onclose } (+3 more)

### Community 107 - "AppearanceTab.svelte"
Cohesion: 0.15
Nodes (12): applyTheme(), currentFont, currentSize, customFont, filteredFonts, fontDropdownOpen, fontSearch, selectTheme() (+4 more)

### Community 108 - "SecurityTab.svelte"
Cohesion: 0.14
Nodes (8): confirmPassword, error, hasPassword, loading, locked, newPassword, saving, showPasswordForm

### Community 109 - "MonitoringBar.svelte"
Cohesion: 0.14
Nodes (12): { connectionId, sshUser }, cpuColor, diskColor, netDown, netUp, Props, ramColor, ramPercent (+4 more)

### Community 110 - "TofuProviderPicker.svelte"
Cohesion: 0.14
Nodes (10): activeProviderIds, activeProviders, catalog, categories, Category, filteredCatalog, { onclose }, Props (+2 more)

### Community 111 - "PluginPermission"
Cohesion: 0.14
Nodes (12): PluginPermission, Http, Notify, SftpList, SftpRead, SftpWrite, SshExec, SshListConnections (+4 more)

### Community 112 - "UiElement"
Cohesion: 0.14
Nodes (14): UiElement, Alert, Button, Code, Column, Divider, Heading, Input (+6 more)

### Community 113 - "SshClientHandler"
Cohesion: 0.26
Nodes (5): cascade_authenticate(), describe_key_load_error(), SshClientHandler, try_agent_auth(), try_agent_auth_inner()

### Community 114 - "sftp_commands.rs"
Cohesion: 0.27
Nodes (9): sftp_delete(), sftp_download(), sftp_list_dir(), sftp_mkdir(), sftp_read_file(), sftp_rename(), sftp_touch(), sftp_upload() (+1 more)

### Community 115 - "devDependencies"
Cohesion: 0.15
Nodes (13): devDependencies, simple-icons, svelte, svelte-check, @sveltejs/adapter-static, @sveltejs/kit, @sveltejs/vite-plugin-svelte, tailwindcss (+5 more)

### Community 116 - "compilerOptions"
Cohesion: 0.15
Nodes (12): ./.svelte-kit/tsconfig.json, compilerOptions, allowJs, checkJs, esModuleInterop, forceConsistentCasingInFileNames, moduleResolution, resolveJsonModule (+4 more)

### Community 117 - "TofuProjectEditor.svelte"
Cohesion: 0.18
Nodes (11): @tauri-apps/plugin-dialog, canSubmit, description, handleClose(), handleSubmit(), loading, name, { open: isOpen, templateId = null, onclose, oncreate } (+3 more)

### Community 118 - "AIPanel.svelte"
Cohesion: 0.17
Nodes (10): aiSettings, chatState, { connectionId, activeTabId, activeTabType }, copiedId, handleKeydown(), handleSend(), inputValue, isConfigured (+2 more)

### Community 119 - "AnsibleAdHocPanel.svelte"
Cohesion: 0.15
Nodes (11): files, hostPattern, inventoryFiles, moduleArgs, moduleName, modules, project, Props (+3 more)

### Community 120 - "AnsibleProjectEditor.svelte"
Cohesion: 0.18
Nodes (10): canSubmit, description, handleClose(), handleSubmit(), loading, name, { open: isOpen, onclose, oncreate }, path (+2 more)

### Community 121 - "MarketplacePanel.svelte"
Cohesion: 0.18
Nodes (11): entries, error, installedIds, installingId, loading, refresh(), registryInput, registryUrl (+3 more)

### Community 122 - "VirtualList.svelte"
Cohesion: 0.15
Nodes (11): containerEl, containerHeight, endIndex, {
		items,
		itemHeight,
		children
	}, offsetY, Props, scrollTop, startIndex (+3 more)

### Community 123 - "snippets.svelte.ts"
Cohesion: 0.23
Nodes (11): addSnippet(), createNode(), editSnippet(), findFirst(), loadSnippets(), rebuildTrie(), removeSnippet(), snippets (+3 more)

### Community 124 - "AnsibleCommand"
Cohesion: 0.15
Nodes (13): AnsibleCommand, AdHoc, GalaxyCollectionInstall, GalaxyCollectionList, GalaxyRoleInstall, GalaxyRoleList, GalaxyRoleRemove, Inventory (+5 more)

### Community 125 - "templates.rs"
Cohesion: 0.23
Nodes (6): aws_rds_template(), aws_static_site_template(), aws_vpc_ec2_template(), docker_nginx_template(), get_project_templates(), k8s_app_template()

### Community 126 - "README.md"
Cohesion: 0.17
Nodes (10): Building from source, Changelog, Contributing, Contributors, Getting started, License, Licensed under the MIT License., Project structure (+2 more)

### Community 127 - "file-explorer.md"
Cohesion: 0.17
Nodes (11): Context Menu, Creating Files and Folders, Deleting, Drag and Drop Upload, File List, How It Works, Inline Editing, Navigating (+3 more)

### Community 128 - "ssh-terminal.md"
Cohesion: 0.17
Nodes (11): Buffer Access, Clipboard, Color Initialization, Jump Host Chains, Local Terminals (PTY), Monitoring Bar, OS Detection, Resize and Scrollback (+3 more)

### Community 129 - "AnsiblePlaybookPanel.svelte"
Cohesion: 0.17
Nodes (10): extraArgs, files, inventoryFiles, playbooks, project, Props, running, selectedInventory (+2 more)

### Community 130 - "loadSessions"
Cohesion: 0.17
Nodes (12): closeContextMenu(), contextNewFolder(), doConnect(), handleConnect(), handleDelete(), handleDeleteFolder(), handleDragStart(), handleEditorSave() (+4 more)

### Community 131 - "AITab.svelte"
Cohesion: 0.17
Nodes (5): aiSettings, apiKeyError, filteredModels, savingApiKey, searchQuery

### Community 132 - "PluginsTab.svelte"
Cohesion: 0.17
Nodes (4): discovering, loading, plugins, pluginsDir

### Community 133 - "TofuBackendPanel.svelte"
Cohesion: 0.17
Nodes (5): backend, catalog, fields, saved, selectedType

### Community 134 - "TofuPlanViewer.svelte"
Cohesion: 0.17
Nodes (7): createCount, deleteCount, expandedResources, loading, replaceCount, summary, updateCount

### Community 135 - "explorer.svelte.ts"
Cohesion: 0.17
Nodes (4): currentPath, entries, FileEntry, followPath

### Community 136 - "TofuProject"
Cohesion: 0.26
Nodes (11): ProjectTemplate, TofuBackendConfig, TofuDataSource, TofuEnvironment, TofuLocal, TofuModuleConfig, TofuOutput, TofuOutputValue (+3 more)

### Community 137 - "opentofu.md"
Cohesion: 0.18
Nodes (10): Adding a data source, Adding a local, Data Sources, Data storage, Generate HCL, Graph, Installing OpenTofu, Interactive canvas (+2 more)

### Community 138 - "plugins.md"
Cohesion: 0.18
Nodes (10): Available hooks, Basic structure, Example: Server Info Plugin, Host API, How plugins work, Limitations, Managing plugins, Security (+2 more)

### Community 139 - "closeContextMenu"
Cohesion: 0.20
Nodes (11): closeContextMenu(), copyToClipboard(), handleCopyFilename(), handleCopyPath(), handleDelete(), handleDownload(), handleEdit(), handleNewFile() (+3 more)

### Community 140 - "KeyPathInput.svelte"
Cohesion: 0.18
Nodes (9): HINT_KINDS, info, isNotFound, isNotKey, isPublic, isValid, Props, suggestions (+1 more)

### Community 141 - "Dropdown.svelte"
Cohesion: 0.18
Nodes (6): dropdownEl, DropdownOption, isOpen, {
		options,
		selected = $bindable(''),
		placeholder = 'Select...',
		onchange
	}, Props, selectedLabel

### Community 142 - "marketplace.ts"
Cohesion: 0.20
Nodes (3): MarketplaceEntry, PluginInfo, PluginPermission

### Community 144 - "plugin/schema.rs"
Cohesion: 0.20
Nodes (7): HOOK_TIMEOUT_DEFAULT_MS, HOOK_TIMEOUT_HARD_CAP_MS, HTTP_REQUEST_TIMEOUT_MS, PluginConfig, PluginInfo, PluginManifest, PluginUiState

### Community 145 - "jump-hosts.md"
Cohesion: 0.20
Nodes (9): Adding a jump host to a saved session, Cross-platform paths, How it works, How to import, Importing from SSH Config, Limitations, Multi-hop chains, Quick Connect with a jump host (+1 more)

### Community 146 - "sync/setup.md"
Cohesion: 0.20
Nodes (9): A Note About Security, Setting Up a Second Device, Step 1: Create a Turso Account, Step 2: Install the Turso CLI (optional but helpful), Step 3: Get Your Organization Name, Step 4: Create a Platform API Token, Step 5: Enter Credentials in Reach, Step 6: Done (+1 more)

### Community 147 - "snippet_commands.rs"
Cohesion: 0.44
Nodes (7): ensure_snippets_vault(), get_snippets_vault_id_if_exists(), snippet_create(), snippet_delete(), snippet_list(), snippet_update(), SNIPPETS_VAULT_NAME

### Community 148 - "AnsibleRolesPanel.svelte"
Cohesion: 0.20
Nodes (7): installName, loading, project, Props, rolesList, running, { target }

### Community 149 - "TitleBar.svelte"
Cohesion: 0.20
Nodes (7): aiConfigured, aiPanelOpen, aiSettings, close(), minimize(), settingsOpen, toggleMaximize()

### Community 150 - "TofuHclPreview.svelte"
Cohesion: 0.20
Nodes (7): activeFile, activeFileIndex, files, loading, { onclose }, Props, writing

### Community 152 - "toasts.svelte.ts"
Cohesion: 0.24
Nodes (7): addToast(), dismissToast(), removeToast(), timers, Toast, toasts, ToastType

### Community 154 - "plan_parser.rs"
Cohesion: 0.33
Nodes (3): compute_attribute_changes(), parse_actions(), parse_plan_json()

### Community 155 - "TofuChangeAction"
Cohesion: 0.22
Nodes (10): TofuAttributeChange, TofuChangeAction, Create, Delete, NoOp, Replace, Update, TofuOutputChange (+2 more)

### Community 156 - "sessions.md"
Cohesion: 0.22
Nodes (8): Auth Methods, Connecting, Creating a Session, Importing from SSH Config, Jump Hosts (ProxyJump), Organizing Sessions, Other Features, Security

### Community 157 - "tunnels.md"
Cohesion: 0.22
Nodes (8): Creating a Tunnel, How It Works Under the Hood, Limitations, Plugin Hooks, Starting and Stopping, Tunnel Cards, Tunnel Types, Typical Use Case

### Community 159 - "TabBar.svelte"
Cohesion: 0.22
Nodes (7): closeTab(), handleCloseWindow(), activePage, activeTab, handleCloseTab(), pages, tabs

### Community 160 - "UpdateDialog.svelte"
Cohesion: 0.22
Nodes (6): buttonDisabled, buttonLabel, { open }, Props, showEscapeHatch, updater

### Community 161 - "TofuWorkspacePanel.svelte"
Cohesion: 0.22
Nodes (4): info, loading, newWorkspaceName, { target }

### Community 162 - "+page.svelte"
Cohesion: 0.22
Nodes (7): activePage, activeTab, connectedSsh, monitoredConnections, pollIntervals, spawnedPtys, tabs

### Community 163 - "installation.md"
Cohesion: 0.25
Nodes (7): Android, Auto-updates, Dependencies, Linux, macOS, Next steps, Windows

### Community 164 - "tofu/schema.rs"
Cohesion: 0.43
Nodes (3): parse_block_attributes(), parse_schema_json(), simplify_type()

### Community 165 - "refresh"
Cohesion: 0.25
Nodes (8): commitNewFile(), commitNewFolder(), commitRename(), confirmDelete(), handleNewFileKeydown(), handleNewFolderKeydown(), handleRenameKeydown(), refresh()

### Community 166 - "i18n.svelte.ts"
Cohesion: 0.29
Nodes (4): changeLocale(), loadEntries(), locale, translations

### Community 167 - "passwords.svelte.ts"
Cohesion: 0.32
Nodes (4): cache, deleteCachedPassword(), save(), setCachedPassword()

### Community 168 - "terminal-buffer.svelte.ts"
Cohesion: 0.25
Nodes (3): BufferReader, readers, readTerminalBuffer()

### Community 170 - "serial_commands.rs"
Cohesion: 0.39
Nodes (5): serial_close(), serial_list_ports(), serial_open(), serial_send(), SerialPortInfo

### Community 171 - "tunnel_commands.rs"
Cohesion: 0.46
Nodes (4): tunnel_create(), tunnel_list(), tunnel_start(), tunnel_stop()

### Community 172 - "TofuVarType"
Cohesion: 0.25
Nodes (7): TofuVariable, TofuVarType, Bool, List, Map, Number, String

### Community 173 - "ai-assistant.md"
Cohesion: 0.29
Nodes (6): Auto-execution, Context awareness, Opening the AI panel, Playbook generation, Running commands, Setup

### Community 174 - "first-run.md"
Cohesion: 0.29
Nodes (6): Identity initialization, Step 1: Language, Step 2: Cloud Sync, Step 3: All done, The main interface, Your first connection

### Community 175 - "scripts"
Cohesion: 0.29
Nodes (7): scripts, build, check, dev, i18n:check, preview, tauri

### Community 176 - "i18n-check.js"
Cohesion: 0.29
Nodes (3): __dirname, __filename, LOCALES_DIR

### Community 178 - "runCommand"
Cohesion: 0.52
Nodes (7): loadStateResources(), runCommand(), setWorkspaceTab(), stateImportResource(), stateMoveResource(), stateRemoveResource(), stateShowResource()

### Community 179 - "monitoring_commands.rs"
Cohesion: 0.43
Nodes (3): monitoring_get_stats(), monitoring_start(), monitoring_stop()

### Community 181 - "Actions"
Cohesion: 0.33
Nodes (6): Actions, Auto Approve, Command buttons, Command output, Execution target, Plan viewer

### Community 182 - "serial.md"
Cohesion: 0.33
Nodes (5): Common Uses, Connecting, How It Works, Port Detection, Supported Platforms

### Community 183 - "shortcuts.md"
Cohesion: 0.33
Nodes (5): App Controls, How Shortcuts Work, Tab Management, Terminal, createTerminal()

### Community 184 - "troubleshooting.md"
Cohesion: 0.33
Nodes (5): Can't Access Vault on New Device, Keychain Access Failed, Shared Vault Not Syncing for a Member, Sync Not Working After Setup, Windows: Turso Connection Issues

### Community 185 - "encryption.md"
Cohesion: 0.33
Nodes (5): Auto-Unlock, How It Works, Local Only, Password Fallback, The Encryption Stack

### Community 186 - "extract-icons.mjs"
Cohesion: 0.33
Nodes (5): simple-icons, found, notFoundList, output, wanted

### Community 187 - "loadDirectory"
Cohesion: 0.33
Nodes (6): commitPathEdit(), handleNodeClick(), handlePathKeydown(), loadDirectory(), navigateTo(), navigateUp()

### Community 188 - "Settings.svelte"
Cohesion: 0.33
Nodes (5): activeTabId, { open, onclose }, Props, TabId, tabs

### Community 189 - "Input.svelte"
Cohesion: 0.33
Nodes (5): floated, focused, inputId, {
		label = '',
		value = $bindable(''),
		type = 'text',
		placeholder = '',
		disabled = false,
		oninput
	}, Props

### Community 190 - "index.ts"
Cohesion: 0.40
Nodes (3): loadLocale(), setLocale(), translations

### Community 194 - "default.json"
Cohesion: 0.33
Nodes (5): description, identifier, permissions, $schema, windows

### Community 195 - "ProviderFieldType"
Cohesion: 0.33
Nodes (6): ProviderFieldType, Bool, Number, Select, Sensitive, String

### Community 196 - "Starlight Starter Kit: Basics"
Cohesion: 0.40
Nodes (4): 🧞 Commands, 🚀 Project Structure, Starlight Starter Kit: Basics, 👀 Want to learn more?

### Community 197 - "development/setup.md"
Cohesion: 0.40
Nodes (4): Clone and run, Other useful commands, Prerequisites, Production builds

### Community 198 - "Providers"
Cohesion: 0.40
Nodes (5): Adding a provider, Configuring a provider, Fetching schema, Providers, Removing a provider

### Community 199 - "introduction.md"
Cohesion: 0.40
Nodes (4): How it's built, Platforms, What's inside, Why another SSH client?

### Community 200 - "shared-vaults.md"
Cohesion: 0.40
Nodes (4): Deleting a Shared Vault, End-to-End Encryption, The Flow, Who Pays for the Database?

### Community 201 - "what-is-turso.md"
Cohesion: 0.40
Nodes (4): Do I Need It?, How Reach Uses It, Pricing, Why Turso?

### Community 202 - "backup.md"
Cohesion: 0.40
Nodes (4): Exporting a Backup, Identity Backup, Importing a Backup, When to Use Backups

### Community 203 - "sharing.md"
Cohesion: 0.40
Nodes (4): Roles, Secret Sharing (One-Off), Security, Vault Sharing

### Community 204 - "docs/tsconfig.json"
Cohesion: 0.40
Nodes (4): exclude, extends, include, astro/tsconfigs/strict

### Community 205 - "What's inside"
Cohesion: 0.40
Nodes (5): Core, Extras, Infrastructure as Code, Productivity, What's inside

### Community 206 - "StatusBar.svelte"
Cohesion: 0.40
Nodes (3): activeTab, connectionStatus, currentTime

### Community 207 - "Toggle.svelte"
Cohesion: 0.50
Nodes (4): {
		checked = $bindable(false),
		label = '',
		disabled = false,
		onchange
	}, onKeydown(), Props, toggle()

### Community 208 - "distro-icons.ts"
Cohesion: 0.40
Nodes (3): DistroIconData, icons, osIdToSlug

### Community 212 - "PluginStatus"
Cohesion: 0.40
Nodes (5): PluginStatus, Disabled, Error, Loaded, Running

### Community 213 - "SessionCommand"
Cohesion: 0.40
Nodes (5): SessionCommand, Close, Data, Ready, Resize

### Community 214 - "architecture.md"
Cohesion: 0.50
Nodes (3): Backend (`src-tauri/`), Frontend (`src/`), How the two halves talk

### Community 215 - "monitoring.md"
Cohesion: 0.50
Nodes (3): How it works, Per-connection stats, What it shows

### Community 216 - "Resources"
Cohesion: 0.50
Nodes (4): Adding a resource, Configuring a resource, Removing a resource, Resources

### Community 217 - "Backend"
Cohesion: 0.50
Nodes (4): Backend, Configuring, Current backend, Selecting a backend

### Community 218 - "Workspaces"
Cohesion: 0.50
Nodes (4): Creating a workspace, Current workspace, Workspace list, Workspaces

### Community 219 - "State"
Cohesion: 0.50
Nodes (4): Importing, Operations per resource, Resource list, State

### Community 220 - "uploadFile"
Cohesion: 0.50
Nodes (4): buildRemotePath(), extractFilename(), handleDrop(), uploadFile()

### Community 221 - "refreshFiles"
Cohesion: 0.50
Nodes (4): formatFiles(), openProject(), refreshFiles(), writeGeneratedFiles()

### Community 224 - "TofuExecutionTarget"
Cohesion: 0.50
Nodes (4): TofuCommandRequest, TofuExecutionTarget, Local, Ssh

### Community 225 - "sessionCreate"
Cohesion: 0.67
Nodes (3): v0.3.7, v0.3.8, sessionCreate()

### Community 226 - "Modules"
Cohesion: 0.67
Nodes (3): Adding a module, Managing modules, Modules

### Community 227 - "Variables"
Cohesion: 0.67
Nodes (3): Adding / editing a variable, Variable table, Variables

### Community 228 - "Projects"
Cohesion: 0.67
Nodes (3): Creating a project, Project list, Projects

### Community 229 - "Environments"
Cohesion: 0.67
Nodes (3): Environments, Managing environments, Setting values

### Community 230 - "Workspace"
Cohesion: 0.67
Nodes (3): Left panel — file browser, Right panel — 13 workspace tabs, Workspace

### Community 231 - "Outputs"
Cohesion: 0.67
Nodes (3): Live values, Output definitions, Outputs

## Knowledge Gaps
- **157 isolated node(s):** `sharp`, `astro/tsconfigs/strict`, `@codemirror/lang-yaml`, `codemirror`, `@tauri-apps/cli` (+152 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 2458 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **37 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `@tauri-apps/api` connect `@tauri-apps/api` to `tofu.ts`, `tofu.svelte.ts`, `ref_lib`, `vault.ts`, `ansible.svelte.ts`, `marketplace.ts`, `sftp.ts`, `Terminal.svelte`, `TitleBar.svelte`, `svelte`, `credentials.ts`, `FileExplorer.svelte`, `package.json`, `ansible.ts`, `ai.svelte.ts`, `snippets.ts`, `sshconfig.ts`, `tunnel.ts`, `ai-chat.svelte.ts`, `AppShell.svelte`, `settings.svelte.ts`, `plugin.ts`, `PluginPanel.svelte`, `pty.ts`, `toolchain.ts`, `EditorWindow.svelte`, `ssh.ts`, `sessions.ts`, `GeneralTab.svelte`?**
  _High betweenness centrality (0.096) - this node is a cross-community bridge._
- **What connects `sharp`, `astro/tsconfigs/strict`, `@codemirror/lang-yaml` to the rest of the system?**
  _157 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `tofu.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.025974025974025976 - nodes in this community are weakly interconnected._
- **Why does `AppState` connect `AppState` to `install.rs`, `tofu_commands.rs`, `VaultManager`, `snippet_commands.rs`, `SshManager`, `TunnelManager`, `plugin/manager.rs`, `ansible_commands.rs`, `serial_commands.rs`, `session_commands.rs`, `tunnel_commands.rs`, `collector.rs`, `pty/manager.rs`, `port.rs`, `monitoring_commands.rs`, `plugin_commands.rs`, `state.rs`, `lib.rs`, `tofu/types.rs`, `TofuProjectManager`, `marketplace_commands.rs`, `ssh_commands.rs`, `AnsibleProjectManager`, `settings_commands.rs`, `credential_commands.rs`, `sftp_commands.rs`?**
  _High betweenness centrality (0.048) - this node is a cross-community bridge._
- **Should `install.rs` be split into smaller, more focused modules?**
  _Cohesion score 0.05555555555555555 - nodes in this community are weakly interconnected._
- **Why does `svelte` connect `svelte` to `PluginsTab.svelte`, `TofuBackendPanel.svelte`, `ref_lib`, `TofuPlanViewer.svelte`, `vault.svelte.ts`, `SessionList.svelte`, `AnsibleWorkspace.svelte`, `TofuDataSourcePanel.svelte`, `AnsibleRolesPanel.svelte`, `TofuHclPreview.svelte`, `VaultPanel.svelte`, `FileExplorer.svelte`, `package.json`, `TofuWorkspace.svelte`, `TofuWorkspacePanel.svelte`, `TofuResourceConfigModal.svelte`, `TofuProjectList.svelte`, `TofuProviderPanel.svelte`, `TofuStatePanel.svelte`, `TunnelManager.svelte`, `AppShell.svelte`, `SnippetPanel.svelte`, `PluginPanel.svelte`, `EditorWindow.svelte`, `SplitPane.svelte`, `TofuEnvironmentPanel.svelte`, `TofuGraphPanel.svelte`, `MarketplacePanel.svelte`, `VirtualList.svelte`?**
  _High betweenness centrality (0.030) - this node is a cross-community bridge._
- **Should `tofu_commands.rs` be split into smaller, more focused modules?**
  _Cohesion score 0.06599597585513078 - nodes in this community are weakly interconnected._