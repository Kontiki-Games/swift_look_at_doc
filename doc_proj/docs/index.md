#Welcome to Swift Look At Manual

##Overview

Swift Look At is a custom animation node for unreal engine. It is similary to the built-in equivalent, but behaves more accurately and naturally.

##Feature

* Keep the frame specified in bone space from rolling while rotating it facing the target, so it can behave more naturally.
* Contrary to the built-in equivalent, Swift Look At applying alpha first, then clamp the rotation, which ensures it is more accurate.
* Visual debugging information is very rich and intuitive, which is convenient for users to locate problems.

##Quick Start

* Open/Create a animation blue print firstly.
* Before we set up the nodes, we first need to determine which bones need to be controlled and their axes.
* For the current example, our goal is to keep mannequin's head always in the direction of the target. Therefore, we determined three bones as control objects: spine01, spine03 and head.
* Then we can insert the first node into the proper place of the graph.
* We can try to insert the first node into the graph and use it to control the head.
