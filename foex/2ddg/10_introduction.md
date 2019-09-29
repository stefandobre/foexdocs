# Introduction

## Requirements/Prerequisites

## Required Database Objects

## Defining FOEX attributes

## About the application you will build in this tutorial

In this tutorial we will create an application to show the different possibilities
with FOEX Plugins on the basis of an imaginary Mail Order Business.

We’ll create a simple FOEX Form to insert new customers, a FOEX updatable grid
with the possibility to insert/update/delete customers. We’ll bind a read-only
FOEX Grid to a FOEX Form as Master/Detail relationship to insert/update/delete
products.

We’ll also create three reliant FOEX Grids with Master/Detail/Detail relationship
on the basis of Order Items, that belong to an Order, which belong themselves
to a customer.

We create a FOEX Tree Grid to summarize Orders, which can be exported as
CSV. On the Start Page we’ll combine all these pages with a FOEX Tree that gives
the option to open all pages in the Center Pane of the same page.
