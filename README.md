# SCM_HW1_Khalid_ALashjaee



# SCM Best Practices

1-Commit Often, Commit Small: Make frequent, focused commits that represent a single logical change. This makes history easier to read and bugs easier to isolate.

2-Use Meaningful Commit Messages: Write messages in the imperative mood (e.g., "Fix login bug" not "Fixed stuff"). Include the what and why.

3-Branch for Every Feature or Fix: Never commit experimental work directly to main. Use short-lived branches and merge via pull requests after review.

4-Review Before Merging: Pull requests should be reviewed by at least one other team member to catch errors and share knowledge.

5-Tag Releases: Use Git tags (e.g., v1.0.0) to mark stable release points, making it easy to reference or roll back to a known good state.

6-Keep Sensitive Data Out: Never commit API keys, passwords, or credentials. Use .gitignore and environment variables instead.
