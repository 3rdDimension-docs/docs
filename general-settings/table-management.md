---
description: >-
  Get to know how to add or remove columns in the table, sort and filter data,
  set alerts and actions
---

# Table management

## Table panels <a href="#table-panels" id="table-panels"></a>

Table panels are represented as a separate class — they all have at least 99% of functionality based on the table view. We use the common table component for all of these panels, so the behavior and features are mostly the same.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LFqorWfAjWaGYwswV2L%2F-LFqoyoJuf9bhBxOV-d9%2FTablePanels.png?alt=media\&token=5dda7b18-9e5b-4293-84cd-f270ef22f97b)

Table panels example

Some table panels have a special toolbar that can be used for Mass-filtering or Quick actions. Other table panels can have no column headers because they don’t really need for understanding the data, thus were hidden to save space; this disables an ability to filter columns data in such panels.

## Columns management <a href="#columns-management" id="columns-management"></a>

Data in table panels are organized in rows and columns, where each item’s (row) parameters are displayed in columns. Not all of the available columns are displayed by default in each table panel. We have selected the most popular and vital per panel and made an ability to modify the columns set as you like.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LFqorWfAjWaGYwswV2L%2F-LFqpMIaZ6Yn9GKi4KqP%2FTableColumns.png?alt=media\&token=480832d6-1781-45e7-9761-b34c15199eb3)

Modify table columns set as you like

Right-click on any column header to see the “_**Column set**_” context menu. Then click on any item in this menu to switch the column’s visibility. You can disable up to 1 column minimum; the last visible column won’t be available to hide.

Other useful features of columns management are sorting and resize. Each column can be dragged by its header between other columns inside the table in order to set the required sequence. You can also drag the vertical borders between two columns to resize them.

## Filtering <a href="#filtering" id="filtering"></a>

The set of rows in the table can be filtered by some data value in their column. There are two ways to apply the filtering:

* Quick table filter
* Advanced table filter

Quick table filter is just another point of access to advanced filtering option, allowing to apply simple filters in several clicks.

Quick table filter can be accessed by clicking the “_**Filter**_” icon in any table column’s header.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LFqorWfAjWaGYwswV2L%2F-LFqqKfyxI-bnUFa7sGg%2FTableQuickFilter.png?alt=media\&token=994801a4-5dd5-4df4-805e-21c9cd458105)

Quick filtering per column

Depending on the data type in a column, the Quick filter will give you the corresponding form for input; currently “_**String**_”, “_**Date/time**_” & “_**Number**_” filtering are supported. Once you select some option — the table rows will be filtered to that ones, containing the selected value. Quick filter can be cancelled by pressing “_**Cancel filtering**_” option.

## Advanced table filter <a href="#advanced-table-filter" id="advanced-table-filter"></a>

In case you would like to apply some more complex filtering (multi-filtering) you can open an advanced filter from panel’s context menu, option “_**Setup actions**_”. This screen has two tabs on the left side, where the first one is an Advanced filter.

You will see your filters here if you have applied some previously in Quick mode.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LFqorWfAjWaGYwswV2L%2F-LFqqvJ1QgfZwbLwX8-P%2FTableAdvancedFiltering.png?alt=media\&token=15bb2602-9410-4a9b-8acf-7f594c01c2e2)

Table advanced filter screen

This screen allows you to Enable/disable filtering as well as set up filtering Conditions. These conditions are set up as:

IF(condition1ANDcondition2...)OR(conditionN...)…IF (condition1 AND condition2 ...) OR (conditionN...) …IF(condition1ANDcondition2...)OR(conditionN...)…

You can setup as many conditions as you like. Due to the possible complex logic of filtering, you are required to apply the changes once you finished the filter set up.

Please notice, not all of applied via Advanced filter conditions can be accessed from the Quick filter.

## Sorting <a href="#sorting" id="sorting"></a>

Each table can be sorted by column value. To sort the table, click on column’s header; you will see a “_**Sorting**_” icon appears. The next click on this header will revert the sorting by this column. You can sort your table only by one column simultaneously.

## Grouping <a href="#grouping" id="grouping"></a>

If you want to organize your rows more precisely, you can use a “_**Rows grouping**_” feature. It allows separating all table items in groups, made from data of some column. Currently, only “_**String**_” data columns are supported for grouping.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LFqorWfAjWaGYwswV2L%2F-LFqs-74I9M4cKwStDeH%2FTableGrouping.png?alt=media\&token=d98a4b7d-4689-4a90-ad85-d6b700079986)

Table grouped by “Side” value

To apply the grouping just right-click on table body and find an option “_**Group by**_”; the second-level of context menu will contain all of available columns that can be grouped by. You can group by one column only. To cancel grouping — follow the previous steps and uncheck the column.

## Table actions <a href="#table-actions" id="table-actions"></a>

This feature allows you to setup certain behavior on some data change in the table. Currently, 3rd Dimension tables support four types of actions:

* Show message
* Play sound
* Color row
* Color cell

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LD6FsRvQ3jgwJIg6O7r%2F-LGPhAKcFnSgrFfJaMpz%2F-LGPhOY5ZRhwFjCRjV2s%2Ftableactions.png?alt=media\&token=40c3e8f2-9b53-47f3-a5df-149e8a1d9c8f)

Table actions per any 3rd Dimension table-based panel

The Table actions functionality can be found under the panel’s context menu option “Setup Actions” and once launched, it opens an “Actions screen”, where you can manage your Actions. The process of Action creation is not complicated.

1. Create an Action item
2. Set conditions (“OR” & “AND”)
3. Set tasks (Show message, Play sound, Color row, Color cell)
4. Save Action
5. Enable Action

## Table actions conditions <a href="#table-actions-conditions" id="table-actions-conditions"></a>

Conditions setup for Table Actions is similar to [Filtering conditions, mentioned earlier](table-management.md#advanced-table-filter).

## Table actions tasks <a href="#table-actions-tasks" id="table-actions-tasks"></a>

Once some condition is met, action will execute the corresponding tasks. Each task will be executed as many times, as the condition was met.

Be careful with the frequently occurring conditions. Some may be met several times per second, so tasks like “_Play sound_” can become disturbing. The “_Show message_” task, fired several times, will be shown as one message box.
