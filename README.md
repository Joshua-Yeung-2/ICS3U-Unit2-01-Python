#!/usr/bin/env python3 
# Created by Joshua Yeung 
# Created on September 2021 
# This program calculats area and perimeter of circle 
# With radius 15mm 

import math 
    
    
def main(): 
    #This function calculats the area and perimeter
    
    print("If a circle has a radius of 15mm: ")
    print("")
    print("Area is {}mm2.".format(math.pi * 15 ** 2))
    print("Perimeter is {}mm.".format(2 * math.pi * 15))
    print("")
    print("Done.")


if __name__ == "__main__":
    main()
