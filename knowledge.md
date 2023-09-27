# Git basics

-   git add `file` -> git add index.html
-   git add . -> đưa toàn bộ thay đổi vào Stage Changes
-   git commit -m'message' -> git commit -m'Add index.html and app.css'
-   git push

# Branch

-   branch
-   branch-name: feat/add-header, optimize-ui, quick-fix
-   git checkout -b `branch` -> git checkout -b optimize-ui
-   Nếu chưa tồn tại dưới local thì ở giao diện Source Control sẽ có button là Publish Branch
-   git push --set-upstream origin `branch` -> git push --set-upstream origin optimize-ui
-   create pull request
-   merge code to branch Master
-   git checkout `branch` -> git checkout master -> chuyển sang nhánh khác
-   git pull -> kéo code từ nhánh về
-   git branch -D `branch` -> git branch -D optimize-ui

# Conflict code

# fetch vs pull

# rebase vs merge

# Other

-   git log --oneline: Log ra những commits
-   git status: Kiểm tra trạng thái của các file
-   ls: Hiển thị danh sách các files và folder
-   clear: Clear terminal

# Git Reset

-   git reset --mixed HEAD/commit_id: Lệnh này thì nó sẽ reset những commit trước đó và những staged changes
-   git reset --soft HEAD/commit_id: Lệnh này chỉ đơn giản là khi chúng ta quên add 1 file nào đó và chỉ muốn add thêm vào sau khi reset
-   git reset --hard HEAD/commit_id: Lệnh này rất nguy hiểm nên cẩn thận khi dùng, nó sẽ xóa những commit trước đó(nếu có)

# Git Revert
