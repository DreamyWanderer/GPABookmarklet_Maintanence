# HCMUS GPA Calculator Bookmarklet (v 2.0.0)

Add a feature to Hcmus Portal, calculate and show your GPA

## What is this?

This is a forked version of GPABookmarlet utility, which is created by [dtrung98's repository](https://github.com/dtrung98/GPABookmarklet).

It has been 4 years since the last updated of original repository, and unfortunately I observed a bug comes from Portal itself which this bookmarklet need to deal with. Although they are not computation bugs (which will be more severe), but they can cause some confusion for user. Recently the portal is receiving frequenly updating, so I think there should be a consistent maintenance for GPABookmarklet to cope with those changings 😢.

Besides that, I also add some minor modifications to this bookmaklet for ~~my~~ user's convenience 😆.

## List of bugs fixed

- ~~Deal with a bug comes from Portal, which duplicate some graded courses (GPABookmarklet takes all of duplication for computing).~~

  - Update: This bug has been solved on my portal page, so I cannot implement this fixing anymore 😶.

  <br>

- The bookmarklet loads the page of full courses and calculate on this page. However, this page may be filled with ungraded courses (although those courses have been). Currently this is a problem for students who took part in the last summer semester.

  - Update: Just found and deleted a letter "1" in source code and done! 😀

  ![Bug 1](Figure/Fix_Bug_1.png)

  <br>

- Checkbox for selecting/unselecting a course to be included in GPA does not work.

  - Update: I am not sure whether the author just decide to remove that functionality for some mysterious reason or not. But I found that this feature is quite useful so I just reimplement it carefully such that it will not conflict with normarl grading calculation 🫣.

## List of minor modification

- Calculate "**Điểm trung bình học tập**" (includes courses that student has not passed).

- You want to save all courses to PC for further analysing, but do not want to type all of them manually? Just click the button "Lưu danh sách học phần đã chọn" and get them as ```csv``` file.

- Enabel sorting courses by the "```Trong GPA```" column.

- Enable searching courses in the table.

- Add **Letter grade** and **4.0 grade** systems.

## Guideline

- Step 1: You must be a HCMUS Student.
- Step 2: Click **[this link](https://dtrung98.github.io/GPABookmarklet)** to know more

````
https://dtrung98.github.io/GPABookmarklet
````
