# CloudM
## Google Workspace 建立用於驗證的服務帳戶
### 使用自動化指令碼建立帳戶
1.開啟 Google Cloud，將帳戶增加「機構政策管理員」權限[（連結）](https://console.cloud.google.com/iam-admin/iam)
將【「停用服務帳戶金鑰建立功能」的政策】[（連結）](https://console.cloud.google.com/iam-admin/orgpolicies/iam-disableServiceAccountKeyCreation)的設定修改規則為「停用」，顯示「未強制執行」
2. 在瀏覽器視窗中開啟 [Cloud Shell 編輯器](https://ssh.cloud.google.com/cloudshell/editor?shellonly=true)。
3. 輸入 
```python3 <(curl -s -S -L https://cutt.ly/cloudmCSA)```
4. 完成 Cloud Shell 視窗中的步驟。
5. 點選「下載」，將內含服務帳戶用戶端 ID 的 JSON 檔案下載到電腦上。
6. 完成「[建立 OAuth 網路用戶端 ID](https://support.google.com/workspacemigrate/answer/9222992)」中的步驟。
