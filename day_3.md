# Day 3

#### XCode iOS Project 만들기

![](1-Welcome_To_Xcode_New_Project-340x320.png)

![](Screen-Shot-2014-07-14-at-3.27.26-PM-480x282.png)

![](2-Select_Single_View_Application-480x278.png)

![](Screen-Shot-2015-09-09-at-1.49.04-PM.png)





#### Hello World 앱 만들기
 
 * `IBOutlet` 변수
 * `IBAction` 함수


 
 ![](HelloWorld01.png) 
 
 ![](HelloWorld02.png)


![](HelloWorld03.png)
```Swift
//  ViewController.swift
//  Hello World

import UIKit

class ViewController: UIViewController {

    @IBOutlet weak var myLabel: UILabel!
    
    @IBAction func buttonPressed(sender: AnyObject) {
        print("button pressed!")
        
        let inputStr = "button pressed"
        myLabel.text = inputStr
    
    }
    override func viewDidLoad() {
        super.viewDidLoad()
        // Do any additional setup after loading the view, typically from a nib.
    }

    override func didReceiveMemoryWarning() {
        super.didReceiveMemoryWarning()
        // Dispose of any resources that can be recreated.
    }

}
```

#### 프로그래밍 문제 : Button Fun 앱 만들기

* 
프로그램을 처음 실행하면 view의 색깔이 노란색`UIColor.yellowColor()` 나타난다. 

* 
`Left button`을 누르면 view의 색깔이 파란색`UIColor.blueColor()`으로 바뀌고, label에는 `"Left button pressed"` 스트링이 출력된다.

* 
`Right button`을 누르면 view의 색깔이 초록색`UIColor.greenColor()`으로 바뀌고, label에는 `"Right button pressed"` 스트링이 출력된다.

![](btnFun01.png) ![](btnFun02.png) ![](btnFun03.png)

