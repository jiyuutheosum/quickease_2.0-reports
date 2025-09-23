## Consolidated Latest Reports (As of September 22, 2025 & September 23, 2025)

---

 [**AUTH**](./web/auth/Sept-23-25.md)
 - **✅ Passed**
    - A001 (Login): User can login successfully; suggest adding eye icon toggle button on the password field for password visibility.
    - A002 (Signup): Users can register with their credentials successfully; suggest adding eye icon toggle button on the password field for password visibility.
    - A003 (Logout): Users can logout successfully without encountering issues.

- **🚧 Partially Passed**
    - A004 (Forgot Password): Encounter an issue on requesting email to change password.

- **🔄 Updates from last iteration**
    - L001 → A001: Suggest adding eye icon toggle button on the password field for password visibility.
    - R003 → A002: Suggest adding eye icon toggle button on the password field for password visibility.

[**FORUM**](./web/forums/Sept-22-25.md)
- **✅ Passed**
    - FO004 (Attachments): Multiple uploads display fine; suggest add delete (“x”) button.
    - FO006 (Delete Post): Deletes successfully; removed from feed.
    - FO007 (Upvote/Downvote): counter updates and works correctly.
    - FO008 (Comment): Adding comments works; displays correctly.
    - FO009 (Threaded Replies): Replies show properly under parent comment.
    - FO010 (Comment Voting): Counters and icons update correctly.
    - FO011 (Edit Comment): Comment updates reflect properly.
    - FO013 (Report): Posts and comments can be reported.
- **🚧 Partially Passed**
    - FO001 (Read/View Posts): Posts and attachments visible; private attachments show error.
        - quiz attachment: selecting private quiz attachment shows private warning page without navigation side bar.
    - FO002 (Search): Works with tags/titles; filters (comments, newest, votes) functional.
        - pagination: selecting next page of the result occurs error.
    - FO003 (Create Post): Posts display correctly; suggest redirect to forum feed after posting.
    - FO005 (Edit Post): Updates reflect in feed and post view.
        - edit with attachment: after editing the post with attachment, the attach shared materials is lost.
    - FO012 (Notifications):
        - Comments: work and redirect properly.
        - Replies: redirect to post, not specific comment.
        - Reports: not implemented.
- **🔄 Updates from last iteration**
    - LF008 → FO008: Suggest implementing Enter key submission for faster and more convenient commenting (Not Implemented).
    - LF015 → FO004: Post attachment confirmation now implemented (Passed).
    - LF001 → FO003: Post creation passed; UX suggestion for redirect (Not Implemented).

 [**QUIZZES**](./web/quizzes/Sept-23-25.md)
 - **✅ Passed**
    - Q001 (Create a quiz manually): User can successfully create a quiz with no errors.
    - Q002 (Answer a quiz): User is able to answer quizzes smoothly without issues.
    - Q003 (Review a quiz): Completed quizzes can be reviewed correctly.
    - Q004 (View all user's attempt and score): Attempts and scores are displayed properly.
    - Q006 (View leaderboard rank quiz): Leaderboard ranking shows accurate results.
    - Q007 (Edit a quiz): Users can edit quizzes successfully.
    - Q008 (Delete a quiz): Quiz deletion works as intended.
    - Q009 (Change quiz visibility): Quizzes can be set to public or private without issues.
    - Q010 (Search a quiz): Quiz search feature functions correctly.

- **🚧 Partially Passed**
    - Q005 (Answer a shared quiz): Errors occur when the shared quiz is deleted by the owner while being accessed or attempted.

- **🔄 Updates from last iteration**
    - Q002: Suggested adding a highlight color for the current item being answered to differentiate it from already answered items (Not Implemented).