
from cmath import pi, rect
import math
from lib2to3 import pygram
from pickle import FALSE, TRUE
from turtle import Screen, width
from xml.etree.ElementTree import PI
import pygame
size = (700, 300)
screen = pygame.display.set_mode(size)
pygame.display.set_caption("My lone work")
done = False
clock = pygame.time.Clock()
WHITE = (255, 255, 255)
BLACK = (0, 0, 0)
RED = (255, 0, 0)
PI = 3.14
print(pygame.font.get_fonts())

while not done:
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            done = True
        elif event.type == pygame.KEYUP:
            print("U pressed UPKEY")
    
    screen.fill(RED)
    pygame.draw.line(screen, BLACK, [150,30], [150,50],3 )
    pygame.draw.line(screen, BLACK, [150,30], [170,30],3 )
    pygame.draw.line(screen, BLACK, [170,30], [170,50],3)
    pygame.draw.line(screen, BLACK, [150,50], [170,50],3)
    y_offset = 0 
    while y_offset < 700:
        pygame.draw.line(screen, BLACK, [0,0+y_offset], [10,10 + y_offset],3)
        pygame.draw.line(screen, BLACK,[690,0+ y_offset], [700,10 + y_offset],3)
        y_offset += 10
    x_offset=0
    while x_offset < 700:
        pygame.draw.line(screen, BLACK, [0 + x_offset,0],[x_offset + 10,10],3)
        x_offset +=10
    pygame.draw.rect(screen, BLACK, [80,80,20,40],3)
    pygame.draw.ellipse(screen, BLACK, [80,80,100,140],5)
    pygame.draw.arc(screen, BLACK, [100,100,250,300],PI , 0, 3)
    pygame.draw.polygon(screen, BLACK, [[0,0],[10,100],[100,50]],7)
    font = pygame.font.SysFont('calibri', 25, True)
    text = font.render("MY GAME",TRUE, BLACK)
    screen.blit(text, [250,250])
    pygame.display.flip()    
    clock.tick(30)
pygame.quit


