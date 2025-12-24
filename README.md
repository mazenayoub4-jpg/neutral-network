# neutral network
This project is a simple binary classification model built using PyTorch. 
import torch
import torch.nn as nn
def main():
  model = nn.Squeential([
      nn.Linear(2, 1)
      nn.Sigmoid()
  )
  x = torch.tensor([[0.5, 1.2]])
  output = model(x)
  print("Prediction:", output)
if __name__ == "__main__":
  main
