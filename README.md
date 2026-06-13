@'
# AKA Lab - Git Safety Foundation Before Vibe Coding

Repository này được tạo ra nhằm mục đích thực hành và xây dựng nền tảng sử dụng Git & GitHub an toàn, chuẩn bị cho quá trình làm việc với AI (Vibe Coding).

## 1. Kiến thức Git cơ bản

- git init
- git branch -M main
- git checkout -b <branch-name>
- git status
- git add <file>
- git commit -m "<message>"
- git push -u origin <branch>
- git pull origin main
- git merge <branch>
- git log --oneline
- git revert <commit-id>

## 2. GitHub Flow

- Tạo branch mới từ main.
- Commit thường xuyên.
- Push lên GitHub.
- Tạo Pull Request.
- Resolve conflict nếu có.
- Merge vào main.

## 3. Ghi chú Bảo mật GitHub

- Không commit API Key hoặc mật khẩu.
- Sử dụng .gitignore.
- Không chia sẻ Personal Access Token.
- Dùng GitHub Secrets khi cần.

## 4. Minh chứng Pull Request

- PR #1: feature-etl -> main
- PR #2: feature-report -> main

## 5. Thực hành Conflict

- Xung đột xảy ra trên README.md.
- Resolve conflict bằng GitHub.
- Commit merge sau khi xử lý.

## 6. Thực hành Revert

Sử dụng:

```bash
git revert <commit-id>
```

để hoàn tác thay đổi một cách an toàn.

## 7. Git khi làm việc với AI

- Tạo branch riêng.
- Review code AI sinh ra.
- Commit nhỏ, dễ revert.
- Không để lộ thông tin nhạy cảm.

## 8. Các branch đã sử dụng

- main
- feature-etl
- feature-report
- fix-documentation
@'
# AKA Lab - Git Safety Foundation Before Vibe Coding

Repository này được tạo ra nhằm mục đích thực hành và xây dựng nền tảng sử dụng Git & GitHub an toàn, chuẩn bị cho quá trình làm việc với AI (Vibe Coding).

## 1. Kiến thức Git cơ bản

- git init
- git branch -M main
- git checkout -b <branch-name>
- git status
- git add <file>
- git commit -m "<message>"
- git push -u origin <branch>
- git pull origin main
- git merge <branch>
- git log --oneline
- git revert <commit-id>

## 2. GitHub Flow

- Tạo branch mới từ main.
- Commit thường xuyên.
- Push lên GitHub.
- Tạo Pull Request.
- Resolve conflict nếu có.
- Merge vào main.

## 3. Ghi chú Bảo mật GitHub

- Không commit API Key hoặc mật khẩu.
- Sử dụng .gitignore.
- Không chia sẻ Personal Access Token.
- Dùng GitHub Secrets khi cần.

## 4. Minh chứng Pull Request

- PR #1: feature-etl -> main
- PR #2: feature-report -> main

## 5. Thực hành Conflict

- Xung đột xảy ra trên README.md.
- Resolve conflict bằng GitHub.
- Commit merge sau khi xử lý.

## 6. Thực hành Revert

Sử dụng:

```bash
git revert <commit-id>
```

để hoàn tác thay đổi một cách an toàn.

## 7. Git khi làm việc với AI

- Tạo branch riêng.
- Review code AI sinh ra.
- Commit nhỏ, dễ revert.
- Không để lộ thông tin nhạy cảm.

## 8. Các branch đã sử dụng

- main
- feature-etl
- feature-report
- fix-documentation
'@ | Set-Content README.md