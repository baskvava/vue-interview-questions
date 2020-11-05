# vue-interview-questions

# What is MVVM?
Model : define, modify data, manipulate business logics
View: UI Component, transfer data model to display as UI interface
View-Model: sychronize View and Model


# What's the difference between Computed and Methods?

- Computed: it will be triggered when data is changed
- Methods: no mather how data changed, it will recalculate

# Why we should should use Vuex?
- Implement single data flow, using "store" to do data management


# There are four major elements
- state: data state
- actions: implement the API behavors
- mutations: be responsible to process state
- getters: get state from ui


# Follow the correct Vuex development flow
[ action -> call API -> waiting -> commit ] => [ mutation -> computed state changed]




