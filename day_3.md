# Day 3

#### Hello World 앱 만들기
 
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

![](btnFun01.png) ![](btnFun02.png) ![](btnFun03.png)

