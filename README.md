charimage
=========

将黑白图片(简笔画)转换成字符图画，字符图画可以在任何允许输入字符的地方显示，例如：


                                                                                                              
                                                       *                                                      
                                                       ***                                                    
                                                        * *    *                                              
                                                 ********* *  **                                              
                                                  ***    *  ** *                                              
                                             ****  ***      *  * ****                                         
                                           **                 ***  **                                         
                                         **                   *   *                                           
                                        *                        ***                                          
                                       *                            **                                        
                                     **                           ** *                                        
                                    **        **                  ****                                        
                                    *        *  *                  *                                          
                                   *             *                  *                                         
                                  *                                 **                                        
                                  *                                  *                                        
                                 *                                   *                                        
                                 *                                    *                                       
                                *                                     *                                       
                                *                                     *                                       
                                              *                       *                                       
                               *            ** **                     *                                       
                               *           **    *                    *                                       
                               *           ****  *                    *                                       
                               *           ****  *                    *                                       
                              ******      ** **  *                    *                                       
                            **     **     ** **  *                   **                                       
                     *******        *      ****  *                   *                                        
                    **              *      ***  *                    *                                        
                    *                *      ****                     *                                        
                    *                *                              *                                         
                    *         *      *                              *                                         
                     *               *                             **                                         
                     **              *                             *                                          
                      **             *                            *                                           
                        **           *                           **                                           
                          ***         *                          *                                            
                             ******   **                       **                                             
                                    ***********               **                                              
                                               **          ***                                                
                                                **    *****                                                   
                                                 *       *                                                    
                                                 *       *                                                    
                                                 *        *                                                   
                                                 *        **                                                  
                                                 *         *                                                  
                                                 *          ** *****                                          
                                                **          ***     **                                        
                                                *          **         **                                      
                                               *          *             *                                     
                                               *         *               *                                    
                                              *         **                *                                   
                                              *         *                  *  ******                          
                                             *          *                  ***     *                          
                                             *          *                   *     **                          
                                            *           *                   *     ***                         
                                            *            *                   *      *                         
                                        *****            *                   **    ***                        
                                     ***   *              *                    *     *                        
                                   **      *               *                *  **    *                        
                                  *        *                **             *****     *                        
                                 *         *                  ****        **        *                         
                                 *          *                    **********         *                         
                                 *          **                                     **                         
                                  *          *                                     * **                       
                                  **          *                                   *   *                       
                                ** *          **                                 **  **                       
                                *      ****    *                                **  **                        
                               *      *    *   *                              **  **                          
                                *     *     *   ****                        ***  **                           
                                **    *      *      *******             ****     *                            
                                 **    **    *             *************         *                            
                                   *     *****                                   **                           
                                    *                                            **                           
                                     **                                          *                            
                                       ****                 ***************  ****                             
                                           ***************                                                    
                                                                                                    *        



安装
====
pip install charimage
                                                                                                            

将简笔画变为字符图画
====================

charimage test/duck.jpg


将简笔画变为字符图画并编码为字符串
==================================

charimage -e test/duck.jpg


将编码字符串解码为字符图画
==========================

charimage -d

然后在提示输入时粘贴编码字符串
