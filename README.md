## Consolidated Latest Reports (As of September 20, 2025 & September 22, 2025)


[**FORUM**](./web/forums/Sept-22-25.md)
- **✅ Passed**
    - FO004 (Attachments): Multiple uploads display fine; suggest add delete (“x”) button.
    - FO006 (Delete Post): Deletes successfully; removed from feed.
    - FO007 (Upvote/Downvote):
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