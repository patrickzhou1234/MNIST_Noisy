<div align="center">
  <h1 style="font-size: 3em; font-weight: bold; color: #2c3e50;">
Improved Noisy MNIST With QNNs  </h1>
  <p style="font-size: 1.2em; color: #34495e;">
    A modified implementation for noisy digit recognition.
  </p>
</div>

<hr style="border: 1px solid #bdc3c7;"/>

<div style="background-color: #ecf0f1; padding: 20px; border-radius: 10px; margin: 20px 0;">
  <h2 style="color: #2980b9; border-bottom: 2px solid #3498db; padding-bottom: 5px;">
    Project Overview
  </h2>
  <p style="font-size: 1.1em; color: #7f8c8d;">
    This project contains a modified version of the code originally presented in the <strong><a href="https://www.tensorflow.org/quantum/tutorials/mnist">MNIST Tutorial</a></strong>. The core logic has been extended and adapted to create a more comprehensive and resilient digit classification model.
  </p>
</div>

<div style="background-color: #f9f9f9; padding: 20px; border-radius: 10px; margin: 20px 0;">
  <h2 style="color: #c0392b; border-bottom: 2px solid #e74c3c; padding-bottom: 5px;">
    Key Modifications
  </h2>
  <ul style="font-size: 1.1em; color: #34495e; list-style-type: none; padding-left: 0;">
    <li style="background: #fff; margin: 10px 0; padding: 15px; border-left: 5px solid #3498db; border-radius: 5px;">
      <strong style="color: #2c3e50;">Expanded Digit Recognition:</strong> The original implementation was limited to classifying only the digits '3' and '6'. This version has been significantly upgraded to recognize and classify all ten digits (0-9) from the MNIST dataset.
    </li>
    <li style="background: #fff; margin: 10px 0; padding: 15px; border-left: 5px solid #e67e22; border-radius: 5px;">
      <strong style="color: #2c3e50;">Testing with Noisy Data:</strong> We have introduced a more challenging testing protocol. The model is now trained on the standard, clean MNIST training dataset but is evaluated on a noisy variant of the MNIST test dataset. This approach assesses the model's generalization capabilities and its performance in more realistic, imperfect conditions.
    </li>
    <li style="background: #fff; margin: 10px 0; padding: 15px; border-left: 5px solid #e67e22; border-radius: 5px;">
      <strong style="color: #2c3e50;">GPU Acceleration</strong>So after I expanded the scope of this tutorial to also include the digits 0-9, the process became extremely slow. To counter this, I added GPU acceleration to make the epochs faster. 
    </li>
  </ul>
</div>

<div style="background-color: #ecf0f1; padding: 20px; border-radius: 10px; margin: 20px 0;">
  <h2 style="color: #27ae60; border-bottom: 2px solid #2ecc71; padding-bottom: 5px;">
    How to Use
  </h2>
  <p style="font-size: 1.1em; color: #7f8c8d;">
    To get started with this project, download the file and then upload to google colab and run it. You will also need the n-MNIST dataset which can be found at <a href="https://csc.lsu.edu/~saikat/n-mnist/">n-MNIST</a>. 
  </p>
  To make the process of running it faster, please use GPU on colab. 
</div>
